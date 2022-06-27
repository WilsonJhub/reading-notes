# Saving Data with Room
-- -  
-- -  

## Accessing data using Room DOAs  

When you use the Room persistence library to store your app's data, you interact with stored data by defining *data access objects*(DAO)  

Each DAO includes methods that offer abstract access to your app's database. At compile time, Room automatically generates implementations of the DAOs that you define.  

-- - 
-- -

### Anatomy of a DAO  

Each DAO can be defined as either an interface or an abstract class. Whichever class you decide to use, you must always annotate `@Dao`  
DAOs do not have properties , but they do define one or more methods for interacting with the data in your app's database.  
-- -
The following code is an example of a simple DAO that defines methods for inserting, deleting, and selecting `User` objects in a *Room* database:
        
    @Dao
    public interface UserDao {
        @Insert
        void insertAll(User... users);

        @Delete
        void delete(User user);

        @Query("SELECT * FROM user")
        List<User> getAll();
    }  

NOTE: *There are two types of DAO methods that define database interactions:*

- ***Convenience methods*** that let you insert, update, and delete rows in your database without writing any SQL code.
- ***Query methods*** that let you write your own SQL query to interact with the database.
-- -
-- -

Source: [Accessing data using Room DOAs](https://developer.android.com/training/data-storage/room/accessing-data#java)
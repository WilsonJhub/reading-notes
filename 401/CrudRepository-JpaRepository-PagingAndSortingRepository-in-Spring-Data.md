#  CrudRepository, JpaRepository, PagingAndSortingRepository in Spring Data
-- -

## Spring Data Repositories  

**JpaRepository** *extends* **PagingAndSortingRepository** and, in turn, the **CrudRepository**.

- ***CrudRepository:*** *Provides CRUD functionality*  
- ***PagingAndSortingRepository:*** *Provides methods to do pagination and sort records*  
- ***JpaRepository:*** *Provides JPA related methods such as flushing the persistence context and delete records in a batch*  
            NOTE: because of the *inheritance* relationship, the *JpaRepository* contains the full API of *CrudRepository* and *PagingAndSortingRepository*.

-- - 
Source:
- [CrudRepository, JpaRepository, PagingAndSortingRepository in Spring Data](https://www.baeldung.com/spring-data-repositories)
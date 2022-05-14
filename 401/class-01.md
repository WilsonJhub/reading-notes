# The Command Line
-----------------  
  
## Command Line:  

	- A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and   feedback will be given to you similarly as text.  
	- The l is ls -l is referred to as an *option*. Options are used to modify the beheavior of a command and normally start with a *-*  


## Basic Navigation:  
	- First thing that was mentioned was the *pwd*. PWD stands for "print working directory". This allows the user to identify their current  
  location of the working directory.   
	- After I ran the pwd command. I ran the ls -l command. This gave me not only a list of the folders within my file, it also gave me the  
  owner of the file (me), the file size (4096Mb), the date and time of file modification, and more.  
	- I have run the command *cd* several times by mistake and have been sent back to the home directory.  
  Then I would have navigate through my  folders to  attain my desired working space again. It turns out that I can just type in *cd [location]* to get to my desired spot.   


## More About Files:   
	- Everything is a file; I appreciate this way of thinking. This is definitely an "ah-hah". If I remember that everything is a folder, I can understand  that the Linux system is only reading my inputs and returning a response.  
	- I don't quite understand the concept of an extentionless file system yet. However, I will post this description of an Extiontionless System below as a  guide to reference for my education. 
		- A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is.  
			The following are common extensions:  
				file.exe - an executable file, or program.  
				file.txt - a plain text file.  
				file.png, file.gif, file.jpg - an image.  


## Manual Pages:   
	- Manual pages are a set of pages that list out every command available on your system including what they do, the specifics of how you run them, and  what command line arguments they accept.  
		To invoke the manual page use the following command:  
			"man <command to look up>"  
	- I typed in " man ls" and I was able to read through the full description on the 'ls' command. This is going to be very useful for myself in the  future. Saves a bit of googling as well.   
	There have been plenty of times in the past where I did not know the use of a command and avoided it altogether.  
	- By typing in 'man -k <search term>' I was able to search and retrieve the exact information that I was looking for.   


## File Manipulation:  
	- If we want to make a new directory we will need to use the 'mkdir' command. When we create a new directory, we will most likely use a good amount of   space with the amount of data inside of our directory.  
		So it is very important that we create a file system that is organized and well maintained because this will give us and our partners clear  descriptions of what is being held inside of these folders.  
	- I am thankful for this command rmdir. I will specifically show that 'rm -r' will remove any directories that contain content within them. This is  especially useful  
		if you don't want to go and manually remove each individual file within the requested directory.  

Sources:
 https://ryanstutorials.net/linuxtutorial/commandline.php  
 https://ryanstutorials.net/linuxtutorial/navigation.php  
 https://ryanstutorials.net/linuxtutorial/manual.php  
 https://ryanstutorials.net/linuxtutorial/aboutfiles.php  
 https://ryanstutorials.net/linuxtutorial/filemanipulation.php  
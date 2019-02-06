# lab-02-part-01-paths-review
My Lab
Lab - Paths and Review
==========
Follow the instructions line-by-line.  

* Type in the commands as is, but ignore the beginning prompt.  
* Enter, tab, up and down are represented by <ENTER><TAB>,<UP> and <DOWN>.  
* "No output" or "nothing happens" are valid answers to any of the questions.
==========

==========
Feel free to use your workstation to test your answers to the questions that don't explicitly tell you to run a command)
==========
==========
1. Write the command that you would use to change to the root directory.
---------- cd /



==========
2. Write the command that you would use to change to your home directory.
---------- Cd~



==========
3. Write the command that you would use to change to your Desktop folder.
----------
 cd desktop
V217-M14:desktop bryan.pierrelouis02$ 

==========
4. What's the absolute path to your home directory?
---------- cd ../



==========
5. What's the absolute path to your Desktop directory?
----------
bryan.pierrelouis02$ cd /var
V217-M14:var bryan.pierrelouis02$ cd ../desktop
-bash: cd: ../desktop: No such file or directory
V217-M14:var bryan.pierrelouis02$ pwd
/var
V217-M14:var bryan.pierrelouis02$ cd /
V217-M14:/ bryan.pierrelouis02$ 


==========
6. What's the absolute path to your Desktop directory?
----------
bryan.pierrelouis02$ cd /applications/eclipse
V217-M14:eclipse bryan.pierrelouis02$ pwd
/applications/eclipse
V217-M14:eclipse bryan.pierrelouis02$ 


==========
7. If you're in your home directory, what's the relative path to your Desktop directory?
---------- ~/

==========
8. If you're in your home directory, how would you create a new directory on your desktop called stuff without changing your directory?  Write your command below.
---------- mkdir stuff
mkdir: stuff: File exists



==========
9. If you're in your root directory, how would you create a new directory on your desktop called more-stuff without changing your directory?  Write your command below.
----------mkdir more-stuff
mkdir: more-stuff: Permission denied



==========
10. If you're in your Desktop directory, how would you create a new directory on your desktop called even-more-stuff?  Write your command below.
----------



==========
11. If you're in your home directory, how would you change to the directory right above it using a relative path (it should bring you to /Users)?  Write your command below.
---------- up arrow



==========
12. If you're in your Desktop directory, how would you change to two directories right above it (again, this should be /Users) using a relative path?  Write your command below.
----------up arrow twice



==========
13. What's the shortcut for changing to the directory that you were just previously in?  For example, if I were in /Volumes... and I changed to /Users/profesor/Desktop, what's a quick way of changing to /Volumes without writing something like cd /Volumes?
----------arrow keys

==========
14. How would you show all of the files (including hidden ones) with detailed (long) information that are on you're Desktop if you're in your home directory?  Write your command below.
----------????


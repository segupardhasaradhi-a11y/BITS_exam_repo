# Question 2 Explanation

- I created the project directories and files for the secure workspace and then set directory permissions to 750 so only the owner and group can access them.
- I restricted the project files to 640 so the contents are readable by the owner and group but not by others.
- The umask value of 0022 influenced the default permission mode, and the final permission model protects the project data from unauthorized access.

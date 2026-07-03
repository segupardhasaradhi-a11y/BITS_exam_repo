# Question 3 Explanation

- I created a regular file, a hard link, and a symbolic link to compare how each link points to the same data.
- The hard link shared the same inode as the original file, while the symbolic link had a different inode and depended on the target path.
- Deleting the original file removed the data only for the symbolic link, because the hard link still referenced the same inode.

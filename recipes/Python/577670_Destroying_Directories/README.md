## Destroying DirectoriesOriginally published: 2011-04-20 23:37:55 
Last updated: 2011-04-21 02:55:31 
Author: Stephen Chappell 
 
When files and directories need to be securely deleted, there are many tools in existence that people can turn to for their needs. While there are many ways one might go about manually deleting files and removing directories, this recipe provides a sample implementation of what may be considered throughout the process. This destructive command line program takes the path to a directory as a command line argument and does its best to render it and its contents unrecoverable. There are much better and inclusive applications than this one, but those wishing to write their own utilities may take some inspiration from this recipe while writing their own tools.
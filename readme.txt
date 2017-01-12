this edit made during the 15th commit.  I will have commit 15comp and 15github.  Once I have committed the changes on my computer locally only, and then also committed changes on GitHub only, I will try to push my computer’s repo up.  That should fail.  Then I will pull the GitHub repo down.  Before, I just left the file “unmerged”, but I did resolve the conflicts by simply adding and committing the “unmerged” readme doc.  This time, I will attempt to abort the merge, as Git suggests in the “Git status” output.


+start
This is my ReadMe for this second repo.

<<<<<<< HEAD
This edit was made on my computer, right after I made the twelfth commit (first on GitHub) on Github.

-end
=======
This edit was made on GitHub, on the master branch. !!!

-end
>>>>>>> 8392c7b5b936e5439c57fc7cbf3dadc9a0ea6383

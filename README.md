1. you see the files changed within each commit in the GitHub Desktop GUI in the HISTORY tab under the current repository, select the commit you want to review in the left-most column, the files changed will be listed in the second column
2. you see the contents of what changed within each file for a commit by following the steps in #1, selecting the file you want to review in the second column, and the right-most column will list the contents of the file
3. you revert out of a commit using the command reset and indicating the commit you want to reset to using HEAD~# where # is the number of commits you want to go back (eg HEAD~1 will go back to the prior commit, HEAD~2 will go to the commit prior to that)
4. HEAD refers to the last commit in the currently check-out bran
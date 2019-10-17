# this project from github for test idea git function

# Git -> compare with branch
## (eg: current branch: branch1 , compared master)
1.  **Don't need**: switch branch1 to master, fetch the code then pull to local.
2.  Just **keep current branch1, then fetch**.
3.  Compare.

# Git -> Repository ->Pull
## (eg: current branch: branch1 , merger master code to local branch1)
1. code merged directly if the merger code does not exist in same line(don't conflict).
2. need to solve conflict if the code diff in the same line.
3. if the master code have merged to local branch1, the merged code have committed, to be push.
4. after above step, if we change the local branch code same with remote branch, but the remote branch don't change, then merge code. 
    the remote code will not be merged, because the code have been merged last time , and remote branch code have not change.
5. if remote code been changed, local don't change. the code will be merged.
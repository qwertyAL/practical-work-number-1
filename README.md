# Git / GitHub entry assistant

---

## Commands for the terminal (Linux)

DEFAULT:
 - *cd <path>* - move to the directory
 - *ls* - output files and child directories from the current directory
 - *mkdir <name>* - create directory
 - *touch <name>* - create file
 - *cat <path / name>* - output the contents of the file
 - *rm <path / name>* - remove dirrectory / file

Git:
 - *git init* - initialization git
 - *git add <path / name>* - adding the file / directory
 - *git commit -m <description of the commit>* - saving file version
 - *git push* - sending files to the remote repository
 - *git remote add <branch> <url / ssh>* - adding the remote repository to the local one
 - *git config <parametr> <value>* - saving value to the config
 
 ---
 
 ## Hash - commit identifier
 **Hashing** is a way to transform a set of data and obtain their “fingerprint”.  
     
 Information about a commit is a set of data: when the commit was made, the contents of the files in the repository at the time of the commit, and a link to the previous, or parent, commit.
   
**Properties**:
 - if a hash is obtained twice for the same set of input data, the result is guaranteed to be the same;
 - if at least something in the source data changes (at least one character), then the hash will also change (and significantly).
   
Git stores a table of *hash → commit* information correspondences. If you know the hash, you can find out everything else: the author and commit date and the contents of the committed files. We can say that the hash is the main commit identifier.

---
title: "Advanced Git commands"
date: 09/04/2023
author: "Miles Wallace"
description: "Advanced Git commands."
tags: ["git",  ]
#font: ""
---
## "Advanced Git commands"
#### _09/04/2023_ 
____
1. git remote  
  
$ git remote add <shortname> <url>  
  
$ git remote add origin  
  
2. git push  
  
$ git push -u <short_name> <your_branch_name>  
  
$ git push -u origin feature_branch  
  
$ git push --set-upstream <short_name> <branch_name>  
  
$ git push --set-upstream origin feature_branch  

3. git fetch   
  
$ git fetch   
  
4. git pull  
  
$ git pull <remote_url>  
  
5. git stash  
  
$ git stash   
  
$ git stash list   
  
$ git stash apply   
  
6. git log  
  
$ git log   
  
$ git log --all  
  
7. git shortlog  
  
$ git shortlog    
  
8. git show  
  
$ git show <your_commit_hash>  
  
9. git rm  
  
$ git rm <your_file_name>  
  
10. git merge  
  
$ git merge <branch_name>  
  
11. git rebase   
  
$ git rebase <base>  
  
12. git bisect   
   
i. To start the git bisect   
  
$ git bisect start    
    
ii. let git bisect know about a good commit    
    
$ git bisect good 'g'     
     
iii. git bisect know about a bad commit    
    
$ git bisect bad 'b'    
  
13. git cherry-pick   
  
$ git cherry-pick <commit-hash>  
  
14. git archive   
  
$ git archive --format zip HEAD > archive-HEAD.zip  
  
15. git pull --rebase  
  
$ git pull --rebase  
  
16. git blame   
  
$ git blame <your_file_name>  
  
17. git tag  
  
$ git tag -a ex  
  
18. git verify-commit  
  
$ git verify-commit <commit>  
  
19. git verify-tag  
  
$ git verify-tag <tag>  
  
20. git diff  
  
i. to compare the working directory with the local repo:  
  
$ git diff HEAD <filename>  
  
ii. to compare two branches:  
  
$ git diff <source branch> <target branch>  
  
21. git citool  
  
$ git citool  
  
22. git mv  
  
$ git mv <old-file-name> <new-file-name>  
  
23. git clean  
  
$ git clean  
  
24. git help  
  
$ git help <git_command>  
  
25. git whatchanged  
  
$ git whatchanged  
# Git Basics (commit, diff, branches)

1. echo "1" >> abc.txt
2. red
3. abc.txt -red. rest>white
4. green
5. echo "2" >> abc.txt
6. No(red), no more untracked - its modified
7. git diff main
8. working tree is empty
9. bad argument no such path
10. git add abc.txt
11. None
12. git diff --staged
13. echo "3" >> abc.txt
14. No, the file is modified and each diff present different compare.
15. we modify the file but we still didn't add to index
16. git reset

# Resolve conflicts

1.git branch -a
2. git checkout -b feature/version1
3. git merge feature/version1
4. done
5. done
   1. done
   2. done
   3. done
   4. done
   5. done
6. didn't take attention what was before. according to the logs only app.py was edit.

# Cherry picking

1. git checkout -b feature/lambda_migration2
2. done
3. done
4. feature
5. didn't understand the q - but if we don't pick what to commit we will face an failed merge


# Changes in working tree and switch branches

1.
2. echo "aa" >> take.txt
3. No error......
4.
5.
6.

# Reset

1. done
2. done
   1. remove the last commit from the current branch
   2. change the index but local modifications are unaffected
   3. nothing but it should lose all uncommitted and untracked changes
   4. The last commit will be removed
3. remove the last commit from the branch, but the file changes will stay in working tree

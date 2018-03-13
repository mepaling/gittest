# gittest

There 2 branches `greeting` and `print-some`
Your mission is to merge the two branches into the `master`
The final result shall greet to a man and print a giraffe.

Following has some git commands:
1. `git clone https://github.com/hsucw/gittest.git`
2. `git checkout -b greeting origin/greeting` (you will enter the branch)
3. `git checkout master` (back to the master branch)
4. `git merge greeting` (merge one branch into the current branch)
5. `git rebase master` (rebase the master branch to current branch)
6. `git add .` (add all file in current directories)
7. `git rebase --continue` (continue the rebase)
8. `git rebase --abort` (stop rebase)  

After execute the program hello.py  

`python3 hello.py World`  


The result shall be:  
```
Hello World

                                       ._ o o
                                       \_`-)|_
                                    ,""       \
                                  ,"  ## |   ಠ ಠ.
                                ," ##   ,-\__    `.
                              ,"       /     `--._;)
                            ,"     ## /
                          ,"   ##    /

```
Hint1: `greeting` contains the code for saying "Hello..", but currently having some error, *plz fix it*.  
Hint2: `print-some` can draw a beautiful giraffe, but the code seems to be *mistakenly removed*.  
Hint3: When facing a conflict, we *never* resolve the conflict on `master` branch.  
Hint4: We can `rebase` a branch to *clean up* some unnecessary commits.  

	  

   ```
   98  git log --graph --pretty=oneline --abbrev-commit
   99  git branch -d featurel
  100  git checkout -b dev
  101  vi readme.txt
  102  git add readme.txt
  103  git commit -m "add merge"
  104  git checkout master
  105  git merge --no-ff -m "merge with no-ff" dev
  106  git log
  107  git log --graph --pretty=oneline --abbrev-commit
  108  git status
  109  git stash
  110  git checkout master
  111  git checkout -b issue-101
  112  vi readme.txt
  113  git add readme.txt
  114  git commit -m "fix bug 101"
  115  git checkout master
  116  git merge --no-ff -m "merged bug fix 101" issue-101
  117  git checkout dev
  118  git status
  119  git stash list
  120  git stash
  121  ls
  122  git stash pop
  123  git stash list
  124  git stash apply stash@{0}
  125  cd learngit
  126  git status
  127  git stash
  128  git checkout master
  129  git checkout -b issue-101
  130  git add readme.txt
  131  git commit -m "fix bug 101"
  132  git checkout master
  133  git merge --no-ff -m "merged bug fix 101" issue-101
  134  git checkout dev
  135  git status
  136  git stash list
  137  git stash apply
  138  git stash pop
  139  git stash list
  140  git checkout -b feature-vulcan
  141  git add vulcan.py
  142  touch vulcan.py
  143  git status
  144  git commit -m "add feature vulcan"
  145  git add vulan.py
  146  git add vulcan.py
  147  git commit -m "add feature vulcan"
  148  git checkout dev
  149  git branch -d feature-vulcan
  150  git branch -D feature-vulcan
  151  git remote
  152  git remote -v
  153  git push origin master
  154  git push origin dev
  155  git clone https://github.com/xiaoni0601/learngit.git
  156  git branch
  157  git checkout -b dev prigin/dev
  158  git checkout -b dev origin/dev
  159  git add env.txt
  160  touch env.txt
  161  vi env.txt
  162  git add env.txt
  163  git commit -m "add env"
  164  git push origin dev
  165  cat env.txt
  166  git add env.txt
  167  git commit -m "add new env"
  168  git push origin dev
  169  git pull
  170  git branch --set-upstream-to=origin/dev dev
  171  git pull
  172  git commit -m "fix env conflict"
  173  git push origin dev
  174  git remote -v
  175  git push origin master
  176  git pull
  177  git status
  178  git log
  179  git rebase
  180  git log
  181  git log --graph --pretty=oneline --abbrev-commit
  182  git push origin master
  183  git log --graph --pretty=oneline --abbrev-commit
  184  git branch
  185  git checkout master
  186  git tag v1.0
  187  git tag
  188  git log --pretty=oneline --abbrev-commit
  189  git tag v0.9 5e30fa1
  190  git tag
  191  git show v0.9
  192  git tag -a v0.1 -m "version 0.1 released" 1094adb
  193  git tag -a v0.1 -m "version 0.1 released" 41a9a1b
  194  git show v0.1
  195  git tag -d v0.1
  196  git push origin v1.0
  197  git push origin --tags
  198  git tag -d v0.9
  199  git push origin :refs/tags/v0.9
  200  git clone https://github.com/xiaoni0601/bootstrap.git
  201  git clone git@github.com:xiaoni0601/bootstrap.git
  202  git clone git@github.com:xiaoni0601/twbs/bootstrap.git
  203  git clone git@github.com:xiaoni0601/bootstrap.git
  204  git config --global color.ui true
  205  git status
  206  cd learngit
  207  git config --global color.ui true
  208  git status
  209  git add App.class
  210  touch App.class
  211  git add -f App.class
  212  git check-ignore -v App.class
  213  git status
  214  git -d App.class
  215  git rm -r --cached <.DS_Store>
  216  cd learngit
  217  ls
  218  git rm -r --cached <App.class>
  219  git rm -r --cached <App>
  220  git rm App.class
  221  git -f App.class
  222  git add -f App.class
  223  ls
  224  git rm -f App.class
  225  ls
  226  git config --global alias.st status
  227  git st
  228  git rm -f .
  229  git last
  230  cat .git/config
  231  cat .gitconfig
  232  cd..
  233  cd ..
  234  git clone https://github.com/me/repo.git
  235  cd repo
  236  git clone https://github.com/xiaoni0601/repo.git
  237  cd learngit
  238  cd Spoon-Knife-master
  239  vi index.html
  240  git add index.html
  241  git commit -m "practise"
  242  git status
  243  git log
  244  cd..
  245  cd ..
  246  cd ..
  247  PATH="$PATH":/usr/local/mysql/bin
  248  mysql -u root -p
  249  cd /usr/local/mysql/bin/
  250  sudo su
  251  cd /usr/local/mysql/bin/
  252  sudo su
  253  sudo rm /usr/local/mysql
  254  sudo rm -rf /usr/local/mysql*
  255  sudo rm -rf /Library/StartupItems/MySQLCOM
  256  sudo rm -rf /Library/PreferencePanes/My*
  257  edit /etc/hostconfig and remove the line MYSQLCOM=-YES-
  258  rm -rf ~/Library/PreferencePanes/My*
  259  sudo rm -rf /Library/Receipts/mysql*
  260  sudo rm -rf /Library/Receipts/MySQL*
  261  sudo rm -rf /private/var/db/receipts/mysql
  262  mysql -u root -p
  263  PATH="$PATH":/usr/local/mysql/bin
  264  mysql -u root -p
  265  mysql -u root -p < init-test-data.sql
  266  mysql -u root -p
  267  mysql -u root -p < C:\Users\Xiaoni Li\Desktop\init-test-data.sql
  268  mysql -u root -p < C:\Users\Xiaoni\Desktop\init-test-data.sql
  269  mysql -u root -p < Users\Xiaonili\Desktop\init-test-data.sql
  270  mysql -u root -p < C:\Usersli\Xiaoni\Desktop\init-test-data.sql
  271  mysql -u root -p < Users/Xiaonili/Desktop/init-test-data.sql
  272  mysql -u root -p < C:Users/Xiaonili/Desktop/init-test-data.sql
  273  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  274  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  275  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  276  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  277  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  278  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  279  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  280  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  281  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  282  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  283  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  284  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  285  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  286  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  287  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  288  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  289  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  290  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  291  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  292  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  293  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  294  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  295  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  296  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  297  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  298  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  299  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  300  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  301  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  302  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  303  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  304  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  305  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  306  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  307  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/test.py
  308  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 "/Users/xiaonili/Desktop/PYCLASS/a leap year.py"
  309  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 "/Users/xiaonili/Desktop/PYCLASS/a leap year.py"
  310  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 "/Users/xiaonili/Desktop/PYCLASS/a leap year.py"
  311  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/jungle_animal.py
  312  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/jungle_animal.py
  313  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/fix_machine.py
  314  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/fix_machine.py
  315  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 "/Users/xiaonili/Desktop/PYCLASS/a leap year.py"
  316  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/nextDay.py
  317  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/nextDay.py
  318  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 "/Users/xiaonili/Desktop/PYCLASS/a leap year.py"
  319  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/daysBetweenDates.py
  320  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/daysBetweenDates.py
  321  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/daysBetweenDates.py
  322  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/daysBetweenDates.py
  323  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/finish_daysBetweenDates.py
  324  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/finish_daysBetweenDates.py
  325  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/finish_daysBetweenDates.py
  326  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/DaysInMonth.py
  327  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/DaysInMonth.py
  328  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/DaysInMonth.py
  329  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/DaysInMonth.py
  330  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/sumLisy.py
  331  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/sumLisy.py
  332  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/sumLisy.py
  333  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  334  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  335  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 -m pip install -U autopep8 --user
  336  pip install --upgrade pip
  337  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  338  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  339  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  340  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  341  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  342  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  343  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  344  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09292019.py
  345  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
  346  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/09302019Lesson.py
  347  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
  348  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
  349  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10082019Lesson13.py
  350  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10082019Lesson13.py
  351  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10082019Lesson13.py
  352  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10082019Lesson13.py
  353  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson14.py
  354  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson14.py
  355  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson14.py
  356  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson14.py
  357  traceroute www.udacity.com
  358  traceroute www.mit.edu
  359  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson15.py
  360  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson15.py
  361  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10092019Lesson15.py
  362  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 52984 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson17.py 
  363  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  364  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  365  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  366  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  367  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  368  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  369  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  370  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  371  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  372  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  373  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  374  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  375  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  376  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  377  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  378  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  379  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  380  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  381  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  382  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  383  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10102019Lesson16.py
  384  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
  385  /Users/xiaonili/.anaconda/navigator/a.tool ; exit;
  386  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 54470 /Users/xiaonili/Desktop/PYCLASS/10122019Lesson18.py 
  387  `chsh -s /bin/zsh`
  388  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 54477 /Users/xiaonili/Desktop/PYCLASS/10122019Lesson18.py 
  389  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 54483 /Users/xiaonili/Desktop/PYCLASS/10122019Lesson18.py 
  390  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/envs/python/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 54492 /Users/xiaonili/Desktop/PYCLASS/10122019Lesson18.py 
  391  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  392  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  393  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  394  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  395  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  396  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3 /Users/xiaonili/Desktop/PYCLASS/10112019Lesson18.py
  397  /Library/Frameworks/Python.framework/Versions/3.7/bin/python3
  398  source /Applications/anaconda3/bin/activate
  399  conda activate python
  400  conda install --name python pytest
  401  source /Applications/anaconda3/bin/activate
  402  conda activate python
  403  /Applications/anaconda3/envs/python/bin/python /Users/xiaonili/Desktop/PYCLASS/10122019Lesson20.py
  404  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/test.py
  405  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10122019Lesson20.py
  406  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10122019Lesson20.py
  407  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10122019Lesson20.py
  408  /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 58065 /Users/xiaonili/Desktop/PYCLASS/10142019Unit6Lesson22.py 
  409  source /Applications/anaconda3/bin/activate
  410  conda activate base
  411  source /Applications/anaconda3/bin/activate
  412  conda activate base
  413  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10132019Lesson20.py
  414  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10132019Lesson20.py
  415  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10142019Unit6Lesson22.py
  416  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10142019Unit6Lesson22.py
  417  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10142019Unit6Lesson22.py
  418  /Applications/anaconda3/bin/python
  419  import time
  420  conda --version
  421  source /Applications/anaconda3/bin/activate
  422  conda activate base
  423  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10142019Unit6Lesson22.py
  424  /Applications/anaconda3/bin/python
  425  /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59667 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  426  source /Applications/anaconda3/bin/activate
  427  conda activate base
  428  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59691 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  429  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59696 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  430  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59702 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  431  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59716 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  432  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59732 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  433  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59740 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  434  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59750 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  435  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59760 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  436  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59764 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  437  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59811 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  438  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59823 /Users/xiaonili/Desktop/PYCLASS/10152019Unit6Lesson22.py 
  439  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59950 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  440  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59956 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  441  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59962 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  442  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 59967 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  443  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60032 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  444  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60044 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  445  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60255 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  446  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60362 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  447  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60403 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson23.py 
  448  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60511 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  449  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60515 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  450  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60519 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  451  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60665 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  452  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60735 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  453  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60887 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  454  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 60891 /Users/xiaonili/Desktop/PYCLASS/10152019Lesson24.py 
  455  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62029 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  456  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62045 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  457  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62055 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  458  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62102 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  459  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62108 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  460  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62164 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  461  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 62175 /Users/xiaonili/Desktop/PYCLASS/10162019Lesson27.py 
  462  source /Applications/anaconda3/bin/activate
  463  conda activate base
  464  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py
  465  /Applications/anaconda3/bin/python /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py
  466  /Applications/anaconda3/bin/python
  467  source /Applications/anaconda3/bin/activate
  468  /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 63372 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  469  conda activate base
  470  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 63505 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  471  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64484 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  472  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64565 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  473  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64570 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  474  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64578 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  475  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64594 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson27.py 
  476  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64714 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson28.py 
  477  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 64967 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson28.py 
  478  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 65044 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson28.py 
  479  cd /Users/xiaonili/Desktop/PYCLASS ; env PYTHONIOENCODING=UTF-8 PYTHONUNBUFFERED=1 /Applications/anaconda3/bin/python /Users/xiaonili/.vscode/extensions/ms-python.python-2019.10.41019/pythonFiles/ptvsd_launcher.py --default --client --host localhost --port 65051 /Users/xiaonili/Desktop/PYCLASS/10172019Lesson28.py 
  480  con
  481  conda
  482  exitr
  483  exit
  484  conda
  485  exit
  486  exit
  487  ls -al /bin/bash
  488  chsh -s /bin/bash
  489  clear
  490  conda
  491  `conda`
  492  `chsh -s /bin/bash`
  493  clear
  494  ls
  495  conda
  496  clear
  497  ls
  498  conda -v
  499  conda
  500  conda list
  501  ls
  502  conda
  503  clear
  504  conda create -n tea_facts python=3
  505  source active tea_facts
  506  source activate tea_facts
  507  soure deactivate tea_facts
  508  source deactivate tea_facts
  509  source deactivate tea_facts
  510  conda deactivate
  511  conda activate tea_facts
  512  conda list
  513  conda numpy pandas matplotlib
  514  conda install numpy pandas matplotlib
  515  conda install jupyter notebook
  516  conda list
  517  history
  518  conda deactivate
  519  ls
  520  conda -h
  521  conda env list
  522  conda env -h
  523  conda env remove -h
  524  conda env remove -n tea_facts
  525  ls
  526  ls env
  527  conda env list
  528  import unicodecsv
  529  history 
  530  conda create -n AB_testing python=3
  531  conda activate AB_testing
  532  conda list
  533  conda install numpy pandas matplotlib
  534  conda install jupyter notebook
  535  import unicodecsv
  536  conda list
  537  import unicodecsv as csv
  538  sudo pip install unicodecsv
  539  import unicodecsv
  540  conda install unicodecsv
  541  conda deactivate AB_testing
  542  conda update -n base -c defaults conda
  543  conda deactivate
  544  conda activate AB_testing
  545  import unicodecsv
  546  conda list
  547  import unicodecsv
  548  python
  549  ls
  550  ls
  551  mkdir ABTest
  552  cd ABTest/
  553  ls
  554  touch 1.py
  555  clear
  556  cd
  557  conda upgrade conda
  558  conda list
  559  conda list
  560  conda install scipy
  561  conda list
  562  clear
  563  conda update --all
  564  conda search *beautifulsoup*
  565  conda env export
  566  conda env create -f environment.yaml
  567  conda env create -f AB_testing.yaml
  568  conda env export
  569  conda env export > environment.yaml
  570  conda env create -f environment.yaml
  571  ls
  572  cd env
  573  ls
  574  env list
  575  cd
  576  ls
  577  env list
  578  cd env
  579  ls
  580  cd
  581  ls
  582  cd opt
  583  ls
  584  cd environment.yaml
  585  cd env
  586  cd
  587  cd env
  588  ls
  589  cd
  590  cd environment.yaml
  591  conda env list
  592  cd
  593  ls
  594  rm environment.yaml
  595  ls
  596  history
  597  history > 1.md
```

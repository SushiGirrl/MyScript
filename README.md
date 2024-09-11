1__
Clone repository\
  git clone <repository-url>\
  \
2__
U need to give the user permission to execute and move the script\
  chmod u+x myCm\
  \
3__
Now move the script to /usr/bin\
  sudo mv myCm /usr/bin\
  (You have to say pls when you want to move files to the super root)\
\
4__
Verify that the files was moved to the right place by using theese commands:\
  cd\
  ls\
\
5__ 
You should now be able to simply use 'myCm' in the same way as 'ls'\
  The output should be: Hello World

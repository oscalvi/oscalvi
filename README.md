# Demo

Some Description!

## subheader

watch youtube git tutorials

Steps to use git & github

1. git clone git@github.com:oscalvi/oscalvi.git  (Github repository)
2. cd oscalvi
3. to do the changes in the repository files and run Git status.
4. git commit -m "Add index.html" -m " Description how to commit new files"
5. git add . (add todo)
6. git config --global --add safe.directory D:/gitclass/oscalvi or
   git config --global --replace-all safe.directory D:/gitclass/oscalvi
7. git config --global user.email "oalvarez36@hotmail.com"
8. git push Origin main (main is the github branch)

step to generate ssh keys

1. ssh-keygen (ssh-keygen -t rsa -b 4096 -C "oalvarez36@hotmail.com")
2. enter the key file name.
3. view the heygen file and copy the key.
4. go to github and in the setting click the add keygen tag and paste it. name it and add the new key.
5. in git-batsh execute  eval "$(ssh-agent -s)"
6. ssh-add testkey
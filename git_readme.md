…or create a new repository on the command line

echo "# HelloWorld" >> README.md

git init

git add README.md

git commit -m "first commit"

http方式： git remote add origin https://github.com/LeifPeng/HelloWorld.git

ssh方式：git remote rm origin（如果用过http），
git remote add origin git@github.com:LeifPeng/HelloWorld.git

git push -u origin master




…or push an existing repository from the command line

git remote add origin https://github.com/LeifPeng/HelloWorld.git

git push -u origin master

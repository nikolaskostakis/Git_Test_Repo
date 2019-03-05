# A simple Git/GitHub Tutorial

## Master Branch

### Local configurations

1. $ git init
2. $ git config
   1. git config user.name “User“
   2. git config user.email user@example.com
3. $ git clone https://github.com/nikolaskostakis/Git_Test_Repo.git

### Tutorial

1. $ git fetch
2. $ git pull origin master
3. Open hello_world.txt and follow the instructions
4. $ git status
5. $ git add hello_world.txt
6. $ git status
7. $ git commit -m "My first commit"
8. Open to_be_ignored.txt and follow the instructions
9. $ git add -A
10. $ git commit -m "My second commit"
11. $ git log
12. $ git branch -a
13. $ git branch myBranch
14. $ git checkout myBranch
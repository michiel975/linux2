Michiel Meyfroodt

## Install Git
```shell	
sudo apt-get install git-all
```

## Install Putty
```shell
sudo apt-get install putty
```

## Install build-essential
```shell
sudo apt-get install build-essential
```

## Create a directory in home called "hello_world"
```shell
pwd
mkdir hello_world
```

## Change to the directory
```shell
cd hello_world
```

## Do a git init
```shell
git init
```

## Create a README.md file with this contents and the actual commands executed
```shell
nano Readme.md
```

## Add, commit and place on github
```shell
git add .
git commit -m "The changes you did"
git push
```

## Add main.cpp to the dir and place the code for a hello world application into it
```shell
pwd
nano main.cpp
```

## Compile the application
```shell
gcc --version
g++ main.cpp -o main
```

## Execute it and add a screenshot
```shell
ls
./main
```

![alt text](/Pictures/screenshot_main.png)

## Add a gitignore for the binary file that was generated
```shell
nano .gitignore
```
Type ```/main``` in the gitignore file

## Make sure to add, commit and push the latest updates
```shell
ssh-keygen -t rsa -C "michiel.meyfroodt@student.vives.be" -b 4096
git status
git add .
git commit -m "Assignment 1"
git push -u origin master
```

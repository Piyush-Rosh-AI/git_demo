# git_demo
1)We start by configuring our local workspace with the respective email id and the author name.It will verify that via a webpage for opening to link.
Usage:   
```bash
  git config –global user.name “[name]”  
```
```bash
  git config –global user.email “[email address]”  
```
Replace the enclosed [] data with your credentials

2)
i)We can than initalise the repo if we are creating a new one.
```bash
git init
```
ii)we can clone the repo if we want to use the existing one[]
```bash
git clone -b [branch name] https://github.com/piyush-roshai/git_demo.git
```
3)Now we have the repo for in our local workspace.It is recommendated that we use different branch to work in our local workspace also called feature branch.This can be done in web github.
To let our system know about the changes done on git web we use
```bash
git fetch
```
Select your branch i.e. feature branch and start using in your local workspace.

4)After the changes you have made you can check them using
```bash
git status
```
5)If you  think you require these changes ,you can finalise them for your local workspace using

```bash
git add .
```
instead of using dot[.] ,you can use respective file names too.

6)If you think these are the final changes than you can commit them tagging along a message about what these changes signifies.

```bash
git commit -m "integrated zed camera for obstacle detection"
```

7)There after you can push your changes to the remote server of the repo

```bash
git push
```
8)You can submit a PR(pull request) as in to compare what changes are done before we can merge it the main branch.

9)Unintionally if you have committed something and would like go to previous commit/some other commit.
You can check the list of commit
```bash
git log
```
You can find the id for that commit and execute
```bash
git reset [id]
```
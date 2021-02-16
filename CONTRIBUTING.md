# Contributing Guidelines  

We are happy to welcome all the contributions  **no contribution is too small.** 


- Before opening a new issue, please **check** if it is already created or not.
- Pull requests will be merged after being **reviewed by a madhav**.
- Create a pull request from a **branch** other than `main`.
- It might take a day to review your pull request. Please have patience and be nice.
- We all are here to learn. You are allowed to make mistakes. That's how you learn, right!

- Pull Requests review criteria:
  - Please fill the **PR template** properly while making a PR
  - You must add your code file into the respective **folders**.
  - Your work must be **original**, written by you not copied from other resources.
  - You must **comment** on your code where necessary.
  - For **frontend changes** kindly share screenshots and work samples of your work before sending a PR.

  
# Submitting Contributions👩‍💻👨‍💻  
Below you will find the process and workflow used to review and merge your changes.  

## Step 0 : Find an issue  🔍
- Take a look at the Existing Issues or create your **own** Issues!  
- Wait for the Issue to be assigned to you after which you can start working on it.  
- Note : Every change in this project should/must have an associated issue.   
![issue](https://github.com/TheLeanProgrammer/TheLeanProgrammer.github.io/issues)  
  
## Step 1 : Fork the Project 🍴
- Fork this Repository. This will create a Local Copy of this Repository on your Github Profile. Keep a reference to the original project in `upstream` remote.  
```  
$ git clone https://github.com/<your-username>/Community-Website  
$ cd <repo-name>  
$ git remote add upstream https://github.com/TheLeanProgrammer/TheLeanProgrammer
```  
![fork](git@github.com:TheLeanProgrammer/TheLeanProgrammer.github.io.git)  
  
- Update your forked repo before working.  
```  
$ git remote update  
$ git checkout <branch-name>  
$ git rebase upstream/<branch-name>  
```  
## Step 2 : Branch  🔖
Create a new branch. Use its name to identify the issue you are addressing.  
```  
# It will create a new branch with name Branch_Name and switch to that branch 
$ git checkout -b branch_name  
```  

## Step 3 : Commit  
- To commit give a descriptive message for the convenience of reviewer by:  
```
# This message get associated with all files you have changed  
$ git commit -m "message"  
```

### Commit message guidelines
- Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```
Any line of the commit message cannot be longer than 100 characters! This allows the message to be easier to read on GitHub as well as in various git tools

### For more details, visit
- [Git commit message guidelines](http://karma-runner.github.io/0.13/dev/git-commit-msg.html)
- [Writing Good Commit Messages: A Practical Git Guide](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)
 

```  
# To push your work to your remote repository  
$ git push -u origin <branch_name>  
```  
  
## Need more help?🤔  
You can refer to the following articles on basics of Git and Github and also contact the Project Mentors, in case you are stuck:  
- [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)  
- [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)  
- [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)  
- [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)  
- [Learn GitHub from Scratch](https://lab.github.com/githubtraining/introduction-to-github)  
  
  
## Tip from us😇  
It always takes time to understand and learn. So, do not worry at all. We know **you have got this**!💪
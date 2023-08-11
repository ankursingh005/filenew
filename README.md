# <h1 align="center"> Docsify Setup Document <b> </b></h1> 



# **Table of content**

- [Overview](#overview)

- [Purpose](#purpose)

- [Steps](#steps)

- [Github](#github)


# **Overview**

>Docsify is a tool that helps you create really nice and easy-to-read documentation websites for your projects. It takes your plain text and makes it look great on the web, with features like smooth scrolling and search. It's a favorite among developers for making user-friendly documentation.


# **Purpose**
>Creating documentation in Markdown, using Docsify, and integrating it with GitHub makes it easy to explain your project, helps people understand and use it, lets you work together with others, and ensures that your information is organized, searchable, and up-to-date. It's like making a user-friendly guidebook for your project that everyone can access and contribute to.

# **Steps**
- Update your system.

![Alt text](docsify/111.png)
- Docsify is built on top of Node.js, so you need to install it along with npm (Node Package Manager).

![Alt text](docsify/222.png)

- Install Docsify 

![Alt text](docsify/333.png)

- Create a directory where you want to host your Docsify documentation. And then change your directory.

![Alt text](docsify/444.png)

- Initialize Docsify in your documentation directory. This will create the necessary files and folder structure.

![Alt text](docsify/555.png)

- Start the Docsify development server to preview your documentation. This will start a local server at http://localhost:3000, where you can see your Docsify documentation.

![Alt text](docsify/666.png)

# **Github**

>Create a github  account and make a repository. To create a GitHub account Go to https://github.com/ Click on "Sign up" and follow the prompts to create your account then  Login github. 

![Alt text](docsify/git01.png)

>Create GitHub Repository
- On GitHub, write the "Name your new repostory" then click on create a new repository button.

![Alt text](docsify/rp1.png)


- Choose a name for your repository. Then Write a short description about your project or documentation. Choose whether the repository should be public or private. Then click create a repository. 

![Alt text](docsify/rp2.png)

>create a new repository on the command line

- **git init** :- "git init" is like setting up a magic box that remembers all the changes you make to your files, so you can easily go back and see what you did later.

![Alt text](<docsify/git init.png>)

- **git add README.md** :-  Command is used to tell Git that you want to include the changes you've made to the README.md file

![Alt text](docsify/read.png)

- **git commit -m "first commit"** :-  Is like saving your work and adding a quick note to remember what you did. It's like taking a snapshot and writing a caption for it.

![Alt text](<docsify/git commit.png>)

- **git branch -M master** :- (git branch) This tells Git you want to work with branches, which are different versions of your project.(M) This is a flag that means you're renaming or moving a branch.(master) This is the name of the branch you're renaming. In Git, "master" is often the default starting point.

![Alt text](<docsify/branch master.png>)

- **git remote add origin https://github.com/ankursingh005/try.git** :- This command is saying, "Git, I want to connect my local project to a place on GitHub called 'origin' using this web address.


- **git push -u origin master** :- Is like sending your local work to your online project's home on GitHub. It's a way to share your changes and keep everything in sync. The -u part helps set up a connection for next time.

![Alt text](<docsify/push master.png>)

>Generate a token to be used as a password when executing the git push -u origin master command.
- Open setting

![Alt text](docsify/token1.png)

- Select Developer settings

![Alt text](docsify/token2.png)

- Select Personal access token (Classic version)

![Alt text](docsify/token3.png)

- Click generate new token

![Alt text](docsify/token4.png)

>Clone the Repository
- Is like making a copy of a project from the internet so you can work on it on your computer.

![Alt text](<docsify/git clone.png>)
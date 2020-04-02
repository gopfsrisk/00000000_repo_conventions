# 00000000_repo_conventions

Welcome to the GitHub profile for the Risk team at Prestige Financial Services.

This profile has been created as a place for us to store the code we write safely and with version control.

To help keep our projects organized, we will create a repository for each project on which we work with the following naming convention:

```YYYYMMDD_project_name```

Additionally, for privacy, each repository needs to be set to **private** and **no data** will be stored on Github. Data should be stored on the shared drive.

Note: if the repository is an installable package (i.e., [prestige](https://github.com/gopfsrisk/prestige), for example) it does not need to use the naming convention and can be public.

Local projects can be *pushed* to GitHub via GitHub's drag and drop or file upload capabilities or via the terminal.

For our purposes (i.e., version control), we need only use very basic terminal commands which can be found [here](https://www.tutsmake.com/upload-project-files-on-github-using-command-line/).

Lastly, including a *brief* description of each project inside the project's ```README.md``` will be helpful to remind us of the purpose of each project.

---

Getting Started:

1. [Generate an SSH key](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) using ```aengland@gopfs.com``` as the email address.

2. [Add the SSH key](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account) to the ```gopfsrisk``` account.

---

To clone, change, and push a repository via SSH (from the terminal):

1. Clone a repository:
  a. ```git clone git@github.com:gopfsrisk/<insert_repo_name_here>.git``` (Note: do not include the "<" and ">" symbols)

2. Make changes locally.

3. Push the repository back to GitHub:
  a. ```git init```
  b. ```git add .```
  c. ```git commit -m "Insert short note here."```
  d. ```git remote add origin git@github.com:gopfsrisk/<insert_repo_name_here>.git```
  e. ```git push origin master```






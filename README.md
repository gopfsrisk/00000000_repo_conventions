# 00000000_repo_conventions

Welcome to the GitHub profile for the Risk team at Prestige Financial Services.

This profile has been created as a place for us to store the code we write safely and with version control.

To help keep our projects organized, we will create a repository for each project on which we work with the following naming convention:

```YYYYMMDD_project_name```

**Do not use spaces** in the names of repositories.

Additionally, for privacy, each repository needs to be set to **private** and **no data** will be stored on Github. Data should be stored on the shared drive.

Note: if the repository is an installable package (i.e., [prestige](https://github.com/gopfsrisk/prestige), for example) it does not need to use the naming convention and can be public.

Local projects can be *pushed* to GitHub via GitHub's drag and drop or file upload capabilities or via the terminal.

For our purposes (i.e., version control), we need only use very basic terminal commands which can be found [here](https://www.tutsmake.com/upload-project-files-on-github-using-command-line/).

Lastly, including a *brief* description of each project inside the project's ```README.md``` will be helpful to remind us of the purpose of each project.

---

Getting Started:

1. [Generate an SSH key](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) using ```aengland@gopfs.com``` as the email address.
* ssh-keygen -t rsa -b 4096 -C "aengland@gopfs.com"
* When prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.
* At the secure passphrase and passphrase comfirmation prompts, hit enter. 

Note: keep the terminal open because you will need to know where to find your SSH key in order to add it to the account in the next step.

2. [Add the SSH key](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account) to the ```gopfsrisk``` account.

---

To clone, change, and push a **private** repository via SSH (from the terminal):

1. Clone a repository:
* ```git clone git@github.com:gopfsrisk/<insert_repo_name_here>.git``` (Note: do not include the "<" and ">" symbols)

2. Make changes locally.

3. Push the repository back to GitHub:
* ```git init```
* ```git add .```
* ```git commit -m "Insert short note here."```
* ```git remote add origin git@github.com:gopfsrisk/<insert_repo_name_here>.git```
* ```git push origin master```

---

To clone, change, and push a **public** repository via SSH (from the terminal):

1. Clone a repository:
* ```git clone https://github.com/gopfsrisk/<insert_repo_name_here>.git``` (Note: do not include the "<" and ">" symbols)

2. Make changes locally.

3. Push the repository back to GitHub:
* ```git init```
* ```git add .```
* ```git commit -m "Insert short note here."```
* ```git remote add origin https://github.com/gopfsrisk/<insert_repo_name_here>.git```
* ```git push origin master```






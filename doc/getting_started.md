<p align="center">
	<a href="../README.md">Home</a> | <b><a href="getting_started.md">Using GitHub Teams</a></b>
</p>

---

<p align="center"><img src="../img/github_logo.PNG" alt="GitHub logo" width=50% height=50% /></p>

#

## How to use GitHub Teams

### [What is GitHub?](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/)

GitHub is a Git repository hosting service.

### [What is Git?](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/)

Git is an open-source version control system started by the creator of Linux (Linus Torvalds). Version control tracks revisions and stores the modifications in a central repository. This allows easy collaboration between and among a team as well as a way to roll back changes if a new alteration results in undesirable consequences.

GitHub is perfect for data analytics and data science for the same reasons it is desirable for software developers. Additionally, GitHub allows for the storage of functions in an easily downloadable library which can be imported and used in scripts.

---

## Getting started with Teams 
### - Prerequisites:
#### - [Install Git](https://git-scm.com/download/win)
#### - Create personal account
#### - Request access to *gopfsrisk* organization)

### Navigate to the [GitHub home page](https://github.com/) and click *Sign in* to access your personal account.

![GitHub Home Page](../img/1_github_home.PNG)

### Log-in to your personal GitHub account.

![Sign-in Page](../img/2_sign_in.PNG)

### From your profile, find the *Organizations* area and click on the Utah Jazz logo to access the *gopfsrisk* organization.

![Profile Page](../img/3_profile_home.PNG)

### Create a new repository by clicking on the *New* button.

![New Repo](../img/4_new_repo.PNG)

### Name the repository and select the *Private* radio button.

![Name Repo](../img/5_name_repo.PNG)

### Scroll down, check the *Initialize this repository with a README*, and click the *Create repository* button.

![README](../img/6_readme.PNG)

### For the first *Commit* (i.e., file upload), the easiset way is to drag and drop the file from *File Explorer* onto the repository.

![Drag and Drop](../img/7_drag_drop.PNG)

### Scroll down and click the *Commit changes* button.

![Commit Changes](../img/8_commit_changes.PNG)

---

### Now, we can use the terminal to *clone* from and *push* to this repository.

---

### Working with private repositories in teams:

To clone, change, and push a **private** repository to teams (from the terminal):

1. Clone a repository:
* ```git clone https://<insert_username_here>:<insert_password_here>@github.com/gopfsrisk/<insert_repository_name_here>.git ``` (*Note*: do not include the "<" and ">" symbols)

**Important**: entering credentials is only required on the **first** clone of a private repository. Subsequent clones and pushes should not require credentials. Thus they will act like a public repository (see below).

2. Make changes locally.

3. Push the repository back to GitHub:
* ```git init```
* ```git add .```
* ```git commit -m "Insert short note here."```
* ```git remote add origin https://github.com/gopfsrisk/<insert_repo_name_here>.git``` (*Note*: this step may not be necessary)
* ```git push origin master```

---

### Working with public repositories in teams:

To clone, change, and push a **public** repository in teams (from the terminal):

1. Clone a repository:
* ```git clone https://github.com/gopfsrisk/<insert_repo_name_here>``` (*Note*: do not include the "<" and ">" symbols)

2. Make changes locally.

3. Push the repository back to GitHub:
* ```git init```
* ```git add .```
* ```git commit -m "Insert short note here."```
* ```git remote add origin https://github.com/gopfsrisk/<insert_repo_name_here>``` (*Note*: this step may not be necessary)
* ```git push origin master```






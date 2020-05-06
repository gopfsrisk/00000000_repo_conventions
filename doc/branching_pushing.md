<p align="center">
	<a href="../README.md">Home</a> | 
	<a href="what_is_git.md">What is Git?</a> |
	<a href="creating_repo.md">Creating Repository</a> |
	<a href="add_repo_to_team.md">Add Repository to a Team</a> |
	<b><a href="branching_pushing.md">Branching and Pushing Files</a></b>
</p>

---

## Working with repositories in teams:

To clone, branch, change, and push a repository in teams (from the terminal):

1. Clone a remote repository to create a local copy:
* ```git clone https://github.com/gopfsrisk/<insert_repo_name_here>``` (*Note*: do not include the "<" and ">" symbols)

*Note*: if you are getting an SSL certificate error, use:
```git -c http.SSLverify=false clone https://github.com/gopfsrisk/<insert_repository_name_here>```

2. CD into the directory named after the repository (or, open a terminal in that directory):
* ```cd <insert_repository_name_here>```

3. By default, we are on the *master* branch. This can be confirmed:
* ```git branch```

4. Make changes locally (i.e., add code/files/etc.).

5. Ensure the local repository is in sync with the remote repository:
* ```git pull```

6. Add all of the changes to the master branch:
* ```git add .```

7. Write a brief commit message decribing what was done:
* ```git commit -m "Insert short note here."```

8. Push the branch back to GitHub:
* ```git push origin master```

*Note*: if upon using the ```git push origin master``` command you are getting an SSL certificate error, use:
```git -c http.SSLverify=false push origin master```

---
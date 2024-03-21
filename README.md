# Jira Ticket:

## Task Title: 
Set up new Git repository and create development branch for 'new-project'

## Task Description:

As a developer, I need a new GitHub repository for 'new-project' and i need a development branch so that I can work on new features without affecting the main branch. 
Readme file should contain step-by-step instructions on how we can do it ourselves.

## Instruction

### Creating a repository

1. Type the following command in the Terminal to create a new repository:
```
git init new-project
```

2. Go to the directory of the created project:
```
cd new-project
```

3. To create a remote repository, log in your [Github]() account. Go to the Repositories tab and click New.
![new repo](/assets/new-repo.png)

4. Type the name of the repository in `Repository name` and click `Create repository`
![create repo](/assets/create-repo.png)

5. Copy the URL and go to the Terminal
![url repo](/assets/url-repo.png)

6. Set up a remote repository on the local computer using th command:
```
git remote add origin <Repository URL>
```

### Create and commit README.md (main branch)

1. Create a README.md file:
```
touch README.md
```

2. Go to VSCode, open project 'new-project' and paste the text into README.md

3. Commit the changes:
```
git add .
git commit -m "init"
```

4. Push changes to a remote repository
```
git push --set-upstream origin main
```

### 

1. Create a new development branch
```
git branch development
```

2. Go to the branch develompent
```
git checkout development
```

3. Go to VSCode, open project 'new-project' and update README.md


## Expected Results:

1. A new branch called "development" is created and the user is able to switch to it successfully.
2. A new file called "README.md" is created and step-by-step instructions is added to it successfully.
3. The changes to the "development" branch are committed with a commit message successfully.
4. The changes from the "development" branch are merged into the "main" branch successfully.


## Definition of Done (DoD):

Link to new-project Readme file
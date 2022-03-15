# github-basics
Testing Github Workflow

# Introduction

To learn basics of GitHub essentials like repositories, branches, commits, and pull requests. Please follow any of the follwing resources

- Official GitHub Docs [Github](https://docs.github.com/en/get-started/quickstart/hello-world)
- Git in 15 Min [Youtube](https://www.youtube.com/watch?v=USjZcfj8yxE).
- Git & GitHub Essentials [Youtube](https://www.youtube.com/watch?v=RGOj5yH7evk)
- Git CheatSheet [Website](https://training.github.com/downloads/github-git-cheat-sheet/)

<div style='margin-top:2rem'></div>

# Getting Started

Let's get your account ready and authorized
1. Login/Access via @increasingly account.
2. Once Logged in create a personal access token for you  account [Check It Here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). This is a system level password for accesing repos which is different than your GitHub Account password
3. If you are on windows use GitBash terminal [Check It Here](https://git-scm.com/downloads)
4. Create a SSH key for your system [Check It Here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). This will help you with making git operations faster as you don't need to put your personal access token everytime.  Please make sure for this to work while cloning your repo you select SSH


<div style='margin-top:2rem'></div>

1. Clone the repo
2. Move/Checkout to develop branch
3. Create your own branch name user/your_name
4. Push the newly created branch
5. Crate a folder with your name on root directory
6. Add a sample.txt inside that file with "My File" written inside
7. Add the changes and commit the change
8. Push the changes
9. Move/Checkout to develop branch
10. Pull latest changes from develop
11. Merge your changes to develop branch and push
12. Move/Checkout to main branch
13. Pull lates changes from main
14. Merge your changes to main branch and push
15. That's it :)

<details>
  <summary>Solution</summary>

1. Clone the repo
```
git clone https://github.com/harsimran-increasingly/github-basics.git
```
2. Move/Checkout to develop branch
```
git checkout develop
```
3. Create your own branch name user/your_name
```
git checkout -b 'user/harsimran'
```
4. Push the newly created branch
```
git push --set-upstream origin user/harsimran
```
5. Crate a folder with your name on root directory
```
.
├── readme.md
├── harsimran
```
6. Add a sample.txt inside that file with "My File" written inside
```
.
├── readme.md
├── harsimran
│   ├── sample.txt
```
7. Add the changes and commit the change
```
git commit -m 'added my file'
```
8. Push the changes
```
git push
```
9. Move/Checkout to develop branch
```
git checkout develop
```
10. Pull latest changes from develop
```
git pull
```
11. Merge your changes to develop branch and push
```
git merge user/harsimran
git push
```
12. Move/Checkout to main branch
```
git checkout main
```
13. Pull lates changes from main
```
git pull
```
14. Merge your changes to main branch and push
```
git merge develop
git push
```
</details>
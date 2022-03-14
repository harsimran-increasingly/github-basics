# github-basics
Testing Github Workflow


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
# UNCA_Astro
Undergraduate observational astronomy resources for ASTR 411 at the University of North Carolina - Asheville (Fall 2016 version)
----------------------------

Committing to the Repository
----------------------------

To keep this repository organized please follow these instructions when writing new material for the course.

Create a directory where you will keep the repository content.
cd into the directory
Initialize the directory as a git repository
```bash
git init
```
Create an alias for the repository
```bash
git remote add origin git@github.com:brittlundgren/UNCA_Astro.git
```
Pull the master branch.
```bash
git pull origin master
```
Create a directory under which you want to add content.
Switch to a new branch
```bash
git checkout -b newbranch
```
Make your edits to the repository. To send changes back to the repository, first add the changes to git, then commit them to the local repository, then push them to the branch.
```bash
git add newmaterial
git commit -m 'Added new material'
git push origin newbranch
```
When finished, switch back to the master branch.
```bash
git checkout master
```
Push your edits to the master branch
```bash
git add newmaterial
git commit -m 'Added new material'
git push origin master
```

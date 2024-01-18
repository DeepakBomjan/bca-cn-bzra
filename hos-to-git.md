
## Steps to create own branch
1. clone remote git repo
```bash
git clone https://github.com/DeepakBomjan/bca-cn-bzra.git
```
2. Go into the git project.
``` cd bca-cn-bzra
```
3. First pull the latest changes
```bash
git pull
```
4. Checkout to main branch
```bash
git checkout main
```
5. Create your assignment branch from main
```bash
git checkout -b assigments-ram
```
6. Check status of new branch
```bash
git status
git log
```
7. Add your assignment file in markdown format
8. Add you new file to git
```bash
git add filename
```
9 Commit your changes
```bash
git commit -m "Commit message here"
```
10. Push your changes to remote
```bash
git push
```
11. Create PR to main branch and add your teacher as reviewer.

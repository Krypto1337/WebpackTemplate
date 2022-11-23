# WebpackTemplate


Webpack config for every single project.
______


## How to use?

Merge Project-b into Project-a

1. Clone this repo anywhere on your PC
2. CD path/to/repoA
3. git remote add repoB /path/to/repoB
4. git fetch repoB --tags
5. git merge -allow-unrelated-histories repoB/<branch_name>
6. git remote remove repoB
7. npm install

### Merge into subdirectory?
 1. CD path/to/repoB
 2. git filter-repo --to-subdirectory-filter repoB
 3. git remote remove repoB
 
 _____
 ## Errors?
 
### Error: Merge conflict in README.md?

1. git add <file> e.g. git add README.md
2. git commit -m ""
3. git push

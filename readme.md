<!-- # Halo Dunia
 # means heading available from 1-6



> block quote
 > means block quote

```
quote
```
``` is a block quote make sure to close it 

**Bold**

 ** becomes bold ** 

*italic* 
 * becomes italic --> 


<!-- this is how to start a repository -->
# How to start a project repository
```sh
# before using git
git config --global user.name <username>
git config --global user.email <email>

# Initialisasi
git init

# add your changes to staged changes
git add <nama-file>
or
git add .

# give the changes a name
git commit -m "<message>"

# push the existing changes
git remote add origin "<the ssh command from github>"


# in case you use new laptop or needed to relog

## this is using ssh
git auth login --git-protocol ssh
 -> login with a web browser 
 -> generate a new ssh key
 -> passphrase just enter
 -> title for ssh just skip

## this is using https
gh auth login
```


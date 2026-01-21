# livel6 ==> level7 :

## Log in to the level : 
    - user : **level6** :
    - password : **level6cyberwizard** :

### 📚 Commands You'll Need
- `cd`: Change directory
- `ls`: List files and directories
- `pwd`: Print working directory
- `cat`: Concatenate and display file contents .
- `tab` key: Autocomplete file names .
- `grep`: Search for patterns within files.
- `|` : Passing the result from one command to another .
- `cp` : copy files and directories

### 🏁 The Challenge
In Level 6, you'll encounter a gzipped file that holds the key to unlocking the next level. To access the password, you'll need to extract the contents of the gzipped file.

**the solution method**
- Use the `cp` command to copy the `password.txt.gz` file to the `tmp/fish.level6` location to bypass  `permissions`- Use the `gzip` command with the `-d` option to extract the file.

**Here's what you need to do** :
- Use the ls command to see the files and directories in your current location.
- Among the listed files, you'll notice a file with a .gz extension, such as secret.txt.gz
- Extract the file and read the contents. 
    - NB you do not have right permissions on your home directory... YOU will need to figure out how to write to a new location, say... the temporary directory
- REMEMBER you need to delete your newly created file
    - `rm /tmp/password.txt`

## Lessons Learned
- In this lesson, you learned how to copy a file to another location to avoid permissions, as well as how to extract a compressed file using the gzip tool.
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)



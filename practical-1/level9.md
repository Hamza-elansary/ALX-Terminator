# livel9 ==> level10 :

## Log in to the level : 
    - user : **level9** :
    - password : **level9elitehaxor** :

### 📚 Commands You'll Need
- `cd`: Change directory
- `ls`: List files and directories
- `pwd`: Print working directory
- `cat`: Concatenate and display file contents .
- `tab` key: Autocomplete file names .
- `grep`: Search for patterns within files.
- `|` : Passing the result from one command to another .
- `cp` : copy files and directories
- `openssl` OpenSSL command line program.
- `sudo` : Execute commands with superuser privileges
### 🏁 The Challenge
In Level 9, you'll encounter a password file that you don't have the necessary permissions to read. To unlock the next level, you'll need to figure out what sudo rights your user has and use them to read the password file.
**the solution method**
- Use the `sudo` command with the `-l` option to get any commands you can type with root privileges.
**Here's what you need to do** :
- Use the ls command to see the files and directories in your current location.
- Among the listed files, you'll notice a file with a name like password.txt, but when you try to read it using the cat command, you'll get a "Permission denied" error.
- To check your sudo rights, use the sudo -l command. This will display the commands that your user is allowed to run with sudo privileges.
- For example: `sudo -l`


## Lessons Learned
- In this lesson, I learned how to use the `sudo` command.
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)


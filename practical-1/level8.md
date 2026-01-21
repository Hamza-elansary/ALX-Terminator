# livel8 ==> level9 :

## Log in to the level : 
    - user : **level8** :
    - password : **level8unhackable** :

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

### 🏁 The Challenge
In Level 8, you'll encounter a file that contains the password encrypted using AES-256-CBC encryption. To unlock the next level, you'll need to decrypt the encrypted password using password found in the second file.

**the solution method**
`openssl enc -aes-256-cbc -d -in encrypted.txt -out decripte.txt`
- `enc` Main encryption/decryption command.
- `-aes-256-cbc` Encryption algorithm: AES-256 in CBC (Cipher Block Chaining) mode .
- `-d` Decrypt mode (use `-e` for encrypt)
- `-in filename` Input file containing encrypted data .
- `-out filename` Output file for decrypted data .
**Here's what you need to do** :
- Use the ls command to see the files and directories in your current location.
- Among the listed files, you'll notice a file with a name like encrypted_password.txt
- To decrypt the encrypted password, use the openssl command with the enc subcommand and the -d option to specify decryption.
    - For example: openssl enc -aes-256-cbc -d -in encrypted_password.txt -out decrypted_password.
    - The -in option specifies the input file (the encrypted password file)
    - The -out option specifies the output file where the decrypted password will be written
        - REMEMBER you need to delete your newly created file
                - `rm /tmp/decrypted.txt`
## Lessons Learned
In this lesson, you will learn how to use the OpenSSL program to decrypt files, using the -in option to insert the encrypted file and the -out option to insert the name of the decrypted file.
## About Me
- [linkedin](https://ma.linkedin.com/in/hamza-el-ansary-799368386)
- [github](https://github.com/settings/profile)


                                                         

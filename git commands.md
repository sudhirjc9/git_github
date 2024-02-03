### git commands
1. git status  --> shows all the folders/files that has been created or updated but has not been commited yet
2. git add <file1 file2 ..etc  or . ( to track all the files)> --> used to tell git to start tracking the files
3. git commit -m "title of the message" -m "Detailes description" --> to commit to git (second -m is optional but good to add a description), first -m is title
4. git push origin master -->
            origin : keyword linked to git repository
            mastre : master is the branch that we wish to push to

## steps to generate ssh key
ssh-keygen -t rsa -b 4096 -C "email@addresss"

This will generate a public and private key, public key is what uploaded to the github.
pbcopy < <apth to the file> -->simple command to copy the key else select and copy
                            
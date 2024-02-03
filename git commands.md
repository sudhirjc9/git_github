### git commands
1. git status  --> shows all the folders/files that has been created or updated but has not been commited yet
2. git add <file1 file2 ..etc  or . ( to track all the files)> --> used to tell git to start tracking the files
3. git commit -m "title of the message" -m "Detailes description" --> to commit to git (second -m is optional but good to add a description), first -m is title
4. git push origin master -->
            origin : keyword linked to git repository
            mastre : master is the branch that we wish to push to

# from local directory (not on github)
5. git init --> to initializea git repo

    error:
        fatal: 'origin' does not appear to be a git repository
        fatal: Could not read from remote repository.

        Please make sure you have the correct access rights
        and the repository exists.

        ## WHEN PUSHING A LOCAL REPO TO GITHUB-->  Since it is not cloned from github git doesn't know which branch to push it to, so we have to create that connection. To do it
        
        1. Create a empty repo on github ( empty repo just to test, we can use an exixting repo as remote to push the code )
6. -->     git remote add origin <remote repository link >
7. -->     git remote -v --> to check the remote connection

8. git push -u origin master --. push to remote repo (-u is for upstream, which can later be removed which will directly push to master then)




## steps to generate ssh key
ssh-keygen -t rsa -b 4096 -C "email@addresss"

This will generate a public and private key, public key is what uploaded to the github.
pbcopy < <apth to the file> -->simple command to copy the key else select and copy
                            
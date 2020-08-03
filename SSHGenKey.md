# Why should we use SSH with GitHub or anything else?


## SSH Keys & Github

### There are 2 methods to clone the repo
``` 
SSH and HTTPS
```
- We have 2 types of repos :
```
SSH - Why
The security problems
private repositories 
Source(GitHUB)- Build (Jenskins onwards) - Test - Production 
# Example of continuous integration. 

Public - not secured and
Private - secured - private
```
- Generate SSH keys on your local system 
- Copy the key from local system to the specific repo on GitHub (ci-start-code)
- .ssh folder where we SSH keys available
- Name new key as your name 

## Generate SSH Key
- cd 
- cd .ssh
- Generate Key Marcus 
- ssh-keygen -t rsa -b 4096 -C "MTse@spartaglobal.com"
- cat filename.pub, copy this
- copy the key to specific key on github repository in settings, deploy keys
- paste the filename.pub 

### It is essential and best practice to write descriptive names i.e shahr
- Now the secured public key form local system which has been copied to our cloud/GitHub

Differnce between deployment and automated delivery  
deployment is done automatically 
used delivery 

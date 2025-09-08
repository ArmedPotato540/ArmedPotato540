3## Lab 02

- Name:Caleb Tisler
- Email Tisler.4@wright.edu

## Part 1 Answers

Full / absolute path to your private key file: 
/home/caleb

Command to SSH to AWS instance: 
```
ssh -i ceg2350key.pem ubuntu@54.227.134.174
```

## Part 2 Answers

1. `chmod u+r bubbles.txt`
    - Means: This command gives the user permission to read the file bubbles.txt 
    - Assessment: This is ok but i think the user of the computer should be allowed to also write in the txt file if needed.
2. `chmod u=rw,g-w,o-x banana.cabana`
    - Means: this command sets the user permission to read and write in banana.cabana, takes the groups permissions to write in banana.cabana, takes others permissions to execute banana.cabana.
    - Assessment: Im not sure what the original permissions are for each field but i think its weird to have other users be able to execute the banana.cabana and not have the owner be able to so i would say this command is very bad, also im not sure if banana.cabana can even be executed to thats somthign else to think about
3. `chmod a=w snow.md`
    - Means: this command sets all directory permissions to write in snow.md
    - Assessment: this is bad because not only can others write in this file but no one can read or execute the file, even the owne. 
4. `chmod 751 program`
    - Means: this command allows the user to read write and execute the program, gives groups the premission to read and execute it, gives others the permission to execute it
    - Assessment: I think this command is okay i like the user permissions and groups permissions but i dont like how an other person can run this program on my computer.
5. `chmod -R ug+w share`
    - Means: Gives write permissons to the user and group recursivly to each file and directory within share.
    - Assessment: this command is very brod but good if you wanted, assuming share is a directory, both the user and group to be able to write in every file then sure go for it.  

## Part 3 Answers

1. Command to create new user: sudo adduser newuser
2. Path to new user's home directory: /home/newuser
3. Evaluate if `ubuntu` can add files to new user's home directory: ubuntu can not add files to the newuser as ubuntu does not have permission to access the newuser
4. Command to switch to new user: sudo su newuser
5. Command(s) to go to new user's home directory: cd newuser
6. Evaluate if new user can add files to user's home directory: yes I can add files to the new users home directory as i am the new user.
7. Command to return to `ubuntu` user: sudo su ubuntu
8. Command to return to `ubuntu` home directory: cd ..

## Part 4 Answers

1. Command(s) to create group named `squad` and add members:
2. Command(s) to add `ubuntu` & user to group `squad`:
3. Command(s) to allow `squad` to view the `ubuntu` user's home directory contents:
4. Command(s) to modify `share` to have group ownership of `squad`:
5. Describe your tests and commands with the user account:
6. Describe the full set of permissions / settings that enable the user to make edits:

## Part 5 Answers

For each, write the command used or answer the question posed.

1. Command(s) to make file using `sudo`: 
2. Command(s) to make file with `root`:
3. Describe / compare ownership and permissions of files:
4. Which account can do what actions? (Type Y or N in columns)

Contents inside of `share`
| Account   | Can View  | Can Edit  | Can Change Permissions    |
| ---       | ---       | ---       | ---                       |
| `root`    |           |           |                           |
| `ubuntu`  |           |           |                           |
| `BOB`     |           |           |                           |

`madewithsudo.txt`
| Account   | Can View  | Can Edit  | Can Change Permissions    |
| ---       | ---       | ---       | ---                       |
| `root`    |           |           |                           |
| `ubuntu`  |           |           |                           |
| `BOB`     |           |           |                           |

5. Command(s) to modify permissions:
6. How to give user account `sudo`:

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

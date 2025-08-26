## Lab 01

- Name: Caleb Tisler
- Email: Caleb.Tisler@gmail.com

## Part 1 - GitHub Profile

1. https://github.com/ArmedPotato540

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |   Displays a help display about windows powershell     |
| Get-Location | pwd    |   Gives me my current location     |
| Get-ChildItem | ls    |   Lists all directorys in that file    |
| mkdir   | mkdir       |   Makes a directory    |
| Set-Location | cd     |   Sets my location to a set file    |
| New-Item | touch      |   Creates an item in a set location     |
| Move-Item | mv        |   Moves an item to a set location    |
| Copy-Item | cp        |   Copys an item from a set location     |
| Remove-Item | rm      |   Removes and item from a set location  |
| notepad.exe | vim     |   Opens notepad    |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows PowerShell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: PS C:\Users\caleb>
2. Create a directory named `DirA`: PS C:\Users\caleb> mkdir DirA
3. Create a directory named `Dir B`: PS C:\Users\caleb> mkdir "Dir B"
4. Go into `DirA`: PS C:\Users\caleb> cd DirA
5. Go into `Dir B` from `DirA`: PS C:\Users\caleb\DirA> cd ..; cd "Dir B"
6. Return to your user's home directory: PS C:\Users\caleb\Dir B> cd ..
7. Create a file named `test.txt`: PS C:\Users\caleb> ni test.txt
8. Move the file named `test.txt` into `DirA`: PS C:\Users\caleb> mv test.txt DirA
9. Contents of `test.txt`: PS C:\Users\caleb\DirA> Get-content test.txt
```
This is text
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: PS C:\Users\caleb\DirA> Copy-Item test.txt copy.txt
11. View the contents of `DirA`: PS C:\Users\caleb\DirA> ls
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: PS C:\Users\caleb\DirA> Copy-Item test.txt fodder.txt, PS C:\Users\caleb\DirA> mv fodder.txt "Dir B"
13. Delete / remove both `fodder.txt` AND `Dir B`: PS C:\Users\caleb\Dir B> Rm fodder.txt, PS C:\Users\caleb> Rm "Dir B"

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

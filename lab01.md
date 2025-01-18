## Lab 01

- Name: Santiago Rached 
- Email: rachedalvarez.2@wright.edu

## Part 1 - GitHub Profile

1. https://github.com/Tw0S41nt

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |Displays help about PowerShell's cmdlets and concepts.|
| Get-Location | pwd    |Shows the path that leads to the file you're currently in.|
| Get-ChildItem | ls    |Shows all of the files and folders in the folder you are in.|
| mkdir   | mkdir       |Creates a new directory.|
| Set-Location | cd     |Sets your location in whatever directory, or folder you ask it to.|
| New-Item | touch      |Creates a new item in the folder you are in, this could be a file or folder.|
| Move-Item | mv        |Moves the item that you specify from one location to another.|
| Copy-Item | cp        |Copies the item that you specify from one location to another.|
| Remove-Item | rm      |Removes whatever file in a folder you specify.|
| notepad.exe | vim     |Launches the notepad application.|

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows

My Command Line Shell is: PowerShell

### Navigating My OS on the Command Line

1. Create a directory named `DirA`:
2. Create a directory named `Dir B`:
3. Go into `DirA`:
4. Go into `Dir B` from `DirA`:
5. Return to your user's home directory:
6. Create a file named `test.txt`:
7. Move the file named `test.txt` into `DirA`:
8. Contents of `test.txt`:
```
1. mkdir DirA
2. mkdir DirB
3. Set-Location .\DirA\
4. PS C:\Users\gerr9\DirA> Set-Location ..\DirB\ 
5. Set-Location ~
6. New-item -Path "C:\Users\gerr9\test.txt" -ItemType File
7. Move-Item -Path "C:\Users\gerr9\test.txt" -Destination "C:\Users\gerr9\DirA\"
8. Get-Content -Path "C:\Users\gerr9\DirA\test.txt"
9. Copy-Item -Path "C:\Users\gerr9\DirA\test.txt" -Destination "C:\Users\gerr9\DirA\copy.txt"
10. PS C:\Users\gerr9\DirA> Get-ChildItem
11. PS C:\Users\gerr9\DirB> Copy-Item -Path "C:\Users\gerr9\DirA\test.txt" -Destination "C:\Users\gerr9\DirB\fodder.txt"
12. PS C:\Users\gerr9\DirB> Remove-Item -Path "C:\Users\gerr9\DirB" -Recurse -Force

```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`:
10. View the contents of `DirA`: 
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:
12. Delete / remove both `fodder.txt` AND `Dir B`:

## Citations

Used Google Ai Feature, Asked how to remove the folder as well as the contents in it and I was able to resolve #12




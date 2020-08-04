
# Some usefull Windows Powershell, batch Scripts/Commands


## Powershell
```powershell
    # Rename Multiple files with specific extension to number
    # *.jpg = search for all jpg files
    # {0}.jpg = output like rename to 1, 2, 3, 4, .. .jpg

    Get-ChildItem *.jpg | %{Rename-Item $_ -NewName (‘{0}.jpg’ -f $nr++)} 
```






    
    

# SR4-backup-n-restore
Scripts to backup and restore Sunrider 4: The Captain's Return game progress on Linux machines, running the game with proton.

Download the repository, and run the scripts.

They literally just copy the folders from
```
[STEAM_LOCATION]/Steam/steamapps/compatdata/2251620/pfx/drive_c/users/steamuser/AppData/Local/Sunrider_4_The_Captains_Return/
```
to
```
[STEAM_LOCATION]/Steam/steamapps/common/Sunrider 4 The Captain's Return/
```
for back up, and vice versa for restore, you can do it manually.

To execute scripts, make them executable, with:
```
$ chmod +x SR4-backup
$ chmod +x SR4-restore
```

Was tested only on my Void-Linux machine, and where ```STEAM_LOCATION``` is ```~/.local/share```. In you case it might be different, but generally the script should be able to find the location. Notify me, if face any issues.

Click to download ZIP archive: https://github.com/Ugusu/SR4-backup-n-restore/archive/refs/heads/main.zip

Click to download TAR archive: https://github.com/Ugusu/SR4-backup-n-restore/archive/refs/heads/main.tar.gz

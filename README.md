DecryptSourceProtection
=======================

Removes source protection from RSLogix 5000 .L5X files

Directions using sk.dat:

1. In RSLogix 5000, right click on the item to be decrypted and click export.
2. Save the .L5X file to a folder
3. Go to http://skdatmonster.github.io/DecryptSourceProtection/index.html
4. Drag the .L5X file into the web page
5. Copy source key from green text
6. Paste source key into new line in sk.dat
7. Open "Configure Source Protection" and make sure it decrypts

Directions using re-importing:

1. In RSLogix 5000, right click on the item to be decrypted and click export.
2. Save the .L5X file to a folder
3. Go to http://skdatmonster.github.io/DecryptSourceProtection/index.html
4. Drag the .L5X file into the web page
5. Copy the decrypted output
6. Paste into a new file, save with extension .L5X
7. Import into RSLogix 5000 in the same location, overwrite objects

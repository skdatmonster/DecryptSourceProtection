DecryptSourceProtection
=======================

Removes source protection from RSLogix 5000 .L5X files

Directions using sk.dat:
1. In RSLogix 5000, right click on the item to be decrypted and click export.
2. Save the .L5X file to a folder
3. Go to https://raw.github.com/skdatmonster/DecryptSourceProtection/master/decrypt.html and save file
4. Open decrypt.html file in browser
5. Drag the .L5X file into the web page
6. Copy source key from green text
7. Paste source key into new line in sk.dat
8. Open "Configure Source Protection" and make sure it decrypts

Directions using re-importing:
1. In RSLogix 5000, right click on the item to be decrypted and click export.
2. Save the .L5X file to a folder
3. Go to https://raw.github.com/skdatmonster/DecryptSourceProtection/master/decrypt.html and save file
4. Open decrypt.html file in browser
5. Drag the .L5X file into the web page
6. Copy the decrypted output
7. Paste into a new file, save with extension .L5X
8. Import into RSLogix 5000 in the same location, overwrite objects

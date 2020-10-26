## AYE Loader CS:GO Cheats Repository
![](https://img.shields.io/badge/support-t.me/ayeahkloader-brightgreen) ![](https://img.shields.io/badge/author-t.me/zrn1x-critical)

This repository adds new cheats and brings back deleted cheats into AYE Loader!
## How to add it in AYE Loader?
 1. Make sure that you using last version of injector
 2. Go to C:\AYE\
 3. Open config.ini
 4. Replace `clangremlini/ayeloader-dll-repo` with `{GITHUB USERNAME}/ayeloader-dll-repo`
 Example: `cheatrepo={GITHUB USERNAME}/ayeloader-dll-repo`
 6. Restart injector.

## What if i have empty cheat list or ERROR?
Make sure you entered variable without spaces, and recheck the link.
If you think there is no errors, remove folder C:\AYE\ and restart injector, then repeat all the steps

## How do i make the same repository?

 1. [Create](https://github.com/new) repository on Github
 2. Upload all dlls in them
 3. Create file `cheats.ini`
 4. Add in first line `[cheats]`
 5. Write cheat name, then = symbol, then dll name.
 Example: if you have cheat, named Aimware and dll name is aimware_crack.dll, you need to write `Aimware=aimware_crack.dll`
 6. Repeat 5 step for all cheats
 7. After cheat strings add `[cheatlist]`
 8. Write `cheatlist=` and write every cheat name with `|` divider, then write |Load DLL
 Example: if you have cheats named Aimware, Nixware and Skeet, write `cheatlist=Aimware|Nixware|Skeet|Load DLL`
 9. Place a new string (important!)
 10. Find out your repository name. It is positioned as in screenshot.
 
 ![](https://i.imgur.com/KH6sKqa.png)
 
 12. Now, if you want to use your repository, you need to replace `clangremlini/ayeloader-dll-repo` with your repository name.

Example of `cheats.ini` file:

  ![](https://i.imgur.com/RSJBiOG.png)



## Good luck!

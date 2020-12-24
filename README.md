## FET Loader CS:GO Cheats Repository
![](https://img.shields.io/badge/support-t.me/fetahkloader-brightgreen) ![](https://img.shields.io/badge/author-t.me/zrn1x-critical)

This repository adds new cheats and brings back deleted cheats into FET Loader!
## How to add it in FET Loader?
 1. Make sure that you using last version of injector
 2. Go to C:\FET Loader\
 3. Open config.ini
 4. Replace `clangremlini/fetloader-dll-repo` with `{GITHUB USERNAME}/fetloader-dll-repo`
 Example: `cheatrepo={GITHUB USERNAME}/fetloader-dll-repo`
 6. Restart injector.

## What if i have empty cheat list or ERROR?
Make sure you entered variable without spaces, and recheck the link.
If you think there is no errors, remove folder C:\FET Loader\ and restart injector, then repeat all the steps

## How do i make the same repository?

 1. [Create](https://github.com/new) repository on Github
 2. Upload all dlls in them
 3. Create file `cheats.ini`
 4. Add in first line `[cheats]`
 5. Write cheat name, then = symbol, then dll name.
 Example: if you have cheat, named Aimware and dll name is aimware_crack.dll, you need to write `Aimware=aimware_crack.dll`
 6. Repeat 5 step for all cheats
 7. After cheat strings add `[cheatlist]`
 8. Write `cheatlist=` and write every cheat name with `|` divider, then write |Custom
 Example: if you have cheats named Aimware, Nixware and Skeet, write `cheatlist=Aimware|Nixware|Skeet|Custom`
 9. After `[cheatlist]` string add `[status]`
 10. Write for each cheat detect status (`UNDETECT`, `DETECT`, `Use at own risk`). If you don't know, write `Use at own risk` on each cheat
 11. Place a new string (important!)
 12. Find out your repository name. It is positioned as in screenshot.
 
 ![](https://i.imgur.com/KH6sKqa.png)
 
 12. Now, if you want to use your repository, you need to replace `clangremlini/fetloader-dll-repo` with your repository name.

Example of `cheats.ini` file:

  ![](https://files.catbox.moe/0z3502.jpg)



## Good luck!

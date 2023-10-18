<!-- ayo why you readin the md file -->
# heres a huge ass list of things to do at school

## sections
 - [software lists](https://github.com/NarwhalKid/school/blob/main/README.md#software-lists)
 - [steam](https://github.com/NarwhalKid/school/blob/main/README.md#steam)
   - [steam info](https://github.com/NarwhalKid/school/blob/main/README.md#steam-info)
   - [getting steam](https://github.com/NarwhalKid/school/blob/main/README.md#steam-info)
   - [using steam after download](https://github.com/NarwhalKid/school/blob/main/README.md#using-steam-after-download)
 - [websites](https://github.com/NarwhalKid/school/blob/main/README.md#websites)
 - [bookmarklets](https://github.com/NarwhalKid/school/blob/main/README.md#bookmarklets)

## software lists
- [bradnails](https://github.com/Project-Bradnails/Bradnails/tree/main)
- [not games](https://drive.google.com/drive/folders/1Fa0E3128_Fq0UTCtHmctLFYdK7BNsH0O)
 - beware of potential viruses (check with [virustotal](https://www.virustotal.com/gui/home/upload)
- [not not games](https://drive.google.com/drive/folders/1nlkkL7v-DCVnzwbaOVpBm_wvDE1bWpdE)
 - a lot of stuff doesn't work as intended

## steam

### steam info
 - many games still wont work correctly because admin is completely required
 - you may need to give yourself a hotspot on data in order to play online

### getting steam
 - download the following:
   - [steam installer](https://drive.google.com/file/d/15eJnb1JOC7o8fTEwX0Bp1fWlx2gU0uJ9/view?usp=share_link)
   - [noadmin.bat](https://drive.google.com/file/d/1WAmmjmAF-gHeVggQKARxvg-lPbWAknOc/view?usp=share_link)
 - find somewhere in the school where you have data (a vpn on school wifi won't work unfortunately) and start a hotspot on your phone and connect to it on your computer (or just do this at home)
 - open wherever you downloaded those files and drag the SteamSetup.exe file onto the noadmin.bat file
 - when it asks for the destination folder, make it `C:\Makeup Work\` or something
 - on the "steam error", click ignore
 - on the "steam service error", click cancel
 - it will take a decent while to open. just be patient
 - once it does, log into your account (obviously)
 - to download games make sure youre connected to a hotspot on data (or again, at home)
 - you can now delete the steam installer and you can delete or move the noadmin bat (the noadmin bat does not work for everything, just some software that asks for admin that doesnt completely need it)
 - i highly recommend the following
   - Steam tab at top
   - Settings
   - Interface
   - Run Steam when my computer starts > off
   - Notify me about additions or changes to my games, new releases, and upcoming releases > off

### using steam after download
 - open file explorer
 - click "Windows (C:)" on the left
 - click whatever folder you made
 - scroll to "steam.exe" and open
 - go through the same steam error steps as before
 - wait for it to open (again, be patient, it could take a while
 - note that even after closing out of the steam window it will likely stay open (click the carrot icon towards the right of your windows taskbar to see steam and open the window if it's already been opened)

## websites
 - note: some of these may require [firefox](https://drive.google.com/file/d/1OyuoQn3aPxvrOcomx2o5sIKXriLcAa72/view?usp=share_link) or to use chrome, click the profile icon, and click guest
 - [ultraviolet](https://54.167.87.46/)
   - as of writing this, you have to use firefox and do the following to use the page:
     - Advanced
     - scroll down
     - Accept the Risk and Continue (dw, its safe, i host it myself on AWS, i just didnt bother setting up a better ssl certificate so we're using a self signed one which makes the browser mad at us)
  - [narwhalkidgames](https://narwhalkidgames5.narwhalkid.repl.co/)
  - [2048verse](https://2048verse.jennafilean.repl.co/)
  - [libreddit (reddit)](https://github.com/libreddit/libreddit-instances/blob/master/instances.md)
    - unfortunately due to the api changes on reddit, there may be temporary issues with an instance and youll have to try another
  - [invidious (youtube)](https://api.invidious.io/)
  - [wikipedia speedruns](https://wikispeedruns.com/)

 ## bookmarklets
  - press ctrl+shift+b if your bookmarks bar is not currently visible
  - highlight the text and drag it to your bookmarks bar to add it as a bookmark. click the bookmark to activate the bookmarklet
  - phone controller
    - `javascript:{var s=document.createElement('script');s.id="ctrljs-js";if(!!!document.getElementById("ctrljs-js")){s.src='https://ctrljs-1.narwhalkid.repl.co/bookmarklet.js',document.body.appendChild(s);}else{document.getElementById("statusView").style.display = document.getElementById("statusView").style.display == "none" ? "" : "none"}};void(0);`
    - click to get a QR code to scan with your phone, click again to toggle the QR code on screen (will not work correctly on some sites or parts of sites)
  - firefox only libreddit changer
    - `javascript:document.location = (document.location + '').replace('www.reddit.com', 'reddit.invak.id')`
    - click the bookmarklet when you go to a reddit.com page and it doesnt work (feel free to change the libreddit instance url (reddit.invak.id to something else)
   
  ## staying quiet
   - you could bring in a usb to keep the files on (or just a straight up bootable OS)
   - keeping files in `C:\Makeup Work\` or something of the sort can help prevent files from being found from the taskbar windows search (of course if this ever leaks to the administrators then they could probably find it there so you may want to keep it somewhere else just because i said that but if you really dont care then that should be good enough)
   - keep apps unpinned from your taskbar
   - be ready to alt+tab away if you have to
   - if youre using steam, turn on the settings i mentioned at the end
   - basically just dont be stupid

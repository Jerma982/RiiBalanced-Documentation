# RiiBalanced Source Code/Code List

🎁ArcIntel's gift to the Mario Kart Wii community becomes my gift to aspiring Mario Kart Wii developers.

📣I will also explain briefly what the codes included in the game mode do along the changes i did to them.

🎈NOTE: I will not provide the MKRiibalanced vehicle stat file to the one's wondering.

💫Why? ArcIntel did all the vehicle related modding. I was just doing code related stuff!

🎎You can either load the codes from the "Riibalanced_CodeList" i left in the Repository download or load your own Codes like in this Guide.

## Ways to "Compile"

🍂There are two ways to "compile" all of this.

- 🌸The "Official" Way (AKA How it was done in the Official Modpack by Me)
- 🏵 And the "Dirty" Way (AKA an easier way, just messier in terms of code)

#### ❓How does the Official Way work?
- 🔰 In the official Riibalanced Mod codes are loaded using the *main.dol* file. This is because if Cheaters try to load external Cheat Codes from Dolphin the game will lose every RiiBalanced feature, losing access to Wiimmfi and Riibalanced's Wiimmfi Region. (This is because in Riibalanced the Custom Region is loaded in the main.dol, not te StaticR.rel)

### 🍀What you will need (Official Way):

- 🍁Common Sense
- 🌼Wiimm's ISO Tools (WIT)
- 🍃boot.dol file matching with your Game's Region
- 🎡The Riivolution Homebrew App
- 🌵Basic Knowledge of Riivolution/XML

## 🎄How to compile the Source Code (Official Way)

- 🎫Download and Install WSZST [here](https://szs.wiimm.de/download.html)
- 🧨Download the Riivolution Homebrew App [here](https://aerialx.github.io/rvlution.net/riivolution.zip)
- 🎇Download the "Riivolution" ZIP file included in this Repository
- 🎉Download the [main.dol](https://avsys.xyz/wiimmfi.zip) corresponding to your Game's Region **(Go into one of the 4 Region Folders and then in "Wiimmfi" move the main.dol file to "YOURMODNAME" on your SD

### Step 1
- 🎆Extract the contents of the **Riivolution Homebrew App** in your Apps folder in your SD/USB
- 🎭Extract the two folders that are inside the **Riivolution** ZIP file in your SD/USB's Root
- ✨Go onto this [website](https://mariokartwii.com/gct/)
- 🧧Paste your Cheat Code in "Paste your code here" and then Click on "Add Code" and then on "Download GCT" (GAME ID and Code Title can be named whatever you want)

It should look like this 

![image](https://user-images.githubusercontent.com/76232148/192621778-22e65c28-b1b2-4f07-a367-509bbb07bf95.png)

❗ Add a ***SINGLE CHEAT CODE*** per GCT File! **If you want to have Multiple Cheat Codes loaded in your mod you need to:**

### Step 2
- 🧿 Remove the previous code you added to your GCT File
- 🧲Paste your new code in "Paste your code here" and repeat the process just with a different "GAMEID" name
- 👜Save the GCT file in the "YOURMODNAME" directory

### Step 3
- 🧵Open a CMD Window in the "YOURMODNAME" directory on your SD
- 🎨Type "wstrt patch main.dol --add-sect GCTNAME.gct -vv" (If you want to load more GCTs **(Cheat Codes)**, copy and paste "--add-sect GCTNAME.gct" as much times as the GCTs you have made.

### Step 4
- 🥽Go into the "riivolution" folder in your SD/USB's Root
- 🔓Open the "ProXML.xml" file with a Text Editor
- 📗Follow the instructions written in the Hashtags, and when you're done delete them.

# That's It
📍For now.

🎃Enjoy the mod you compiled!

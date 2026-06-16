ReaperGleam – Installation Guide 
This is the full setup guide for installing ReaperGleam. The goal here is to make the process easy to follow, even if you’ve never installed a huge Wabbajack list before. Just go step by step and don’t skip anything — the list is massive, and missing even one requirement can break the install.
1. Before You Start
     ReaperGleam is a huge modlist, so your PC needs to be ready for it. Make sure your system meets the recommended specs and that you have enough storage space. The full install takes around 523 GB, so plan ahead.
2. Fixing Pagefile / Memory Crashes
    Big Skyrim lists eat RAM like crazy. If Windows runs out, the game will crash even if you have a ton of physical memory. To avoid this, you must set a large pagefile:
      1.	Press Windows + R
      2.	Type sysdm.cpl
      3.	Go to Advanced → Performance → Settings
      4.	Open the Advanced tab
      5.	Under Virtual Memory, click Change
      6.	Turn off “Automatically manage paging file size”
      7.	Choose the drive Skyrim is on
      8.	Set Custom Size
        o	Minimum: 20480 MB
        o	Recommended: 40960 MB
      9.	Click Set, then OK
     10.	Restart your PC
          This step is not optional. Even 256 GB of RAM won’t save you if Windows refuses to allocate memory.
3. Required Software
      Install the following:
        •	Microsoft Visual C++ Redistributables (x64) Download the latest version under “Visual Studio 2015–2022”
        •	.NET Runtime
        •	Disable or exclude your modding folders from OneDrive (OneDrive breaks Wabbajack installs constantly)
4. Accounts You Need
      You must have a Nexus Mods account. Premium is strongly recommended — otherwise you’ll be clicking download buttons for hours.
5. Folder Setup
      Create these folders on the root of a drive (example: C:\):
        •	C:\ReaperGleam – where the modlist installs
        •	C:\wabbajack – where Wabbajack itself goes
        •	C:\ResourceDownloads – where all downloaded mods go
        •	C:\SkyrimGAME – a clean Steam library for Skyrim
      Make sure your antivirus ignores these folders. If it doesn’t, it will delete files Wabbajack needs.
      If you only have one drive, just make sure none of these folders are inside Program Files.
6. Steam Setup
      Before installing Skyrim:
        •	Disable Steam Overlay
        •	Set Skyrim’s language to English
        •	Change updates to “Only update when I launch the game”
        •	Disable Steam Cloud
      Then add a new Steam library pointing to C:\SkyrimGAME. If Steam refuses to create a new library on the same drive, follow the workaround linked in the original readme.
7. Fresh Skyrim Install
      You need a completely clean Skyrim SE/AE install.
        1.	Uninstall Skyrim through Steam
        2.	Delete leftover files in the Skyrim folder
        3.	Delete:
          o	%localappdata%\Skyrim Special Edition
          o	Documents\My Games\Skyrim Special Edition
4.	Reinstall Skyrim into C:\SkyrimGAME
5.	Launch the game once
      o	Let Creation Club content install
      o	Don’t alt tab
6.	Close the game
7.	Install the Creation Kit into the same Steam library
      This ensures all registry entries and base files are correct.
8. Installing ReaperGleam Through Wabbajack
      Now you’re ready for the actual modlist install.
        1.	Install Wabbajack into C:\wabbajack
        2.	Open it and log into your Nexus account
        3.	Select the ReaperGleam modlist
        4.	Set:
          o	Installation Location: C:\ReaperGleam
          o	Download Location: C:\ResourceDownloads
        5.	Start the installation
        6.	If “Overwrite” appears, check it
        If anything fails, re check the steps above. 99% of install issues come from missing a requirement or having Skyrim installed in the wrong place.
9. After Installation
      Once Wabbajack finishes:
        •	Launch Mod Organizer 2 from inside the ReaperGleam folder
        •	Make sure the controls and gamepad settings match the included images
        •	Start the game from SKSE inside MO2
At this point, everything should be ready to play.


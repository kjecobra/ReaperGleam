![Overview banner](Images/overview.png)

ReaperGleam is a modernization of ElderGleam 4.0.2 rebuilt for the Skyrim Anniversary Edition (1.6.1170). The list replaces ENB‑era lighting assumptions with a Community Shader–driven PBR workf[...]

Built on engine fixes and modern SKSE-based systems, the modlist emphasizes updated animation behavior, reliable LOD generation, and runtime stability improvements. Expect improved materials and li[...]


![System requirements banner](Images/system%20requirements.png)

<div align="center">

## System requirements

| Requirement  | Minimum | Recommended |
|---|---:|---:|
| Processor    | i5 9th Gen or equivalent | i7 9th Gen or higher |
| RAM          | 16 GB DDR4 + 40 GB pagefile | 16 GB DDR5 + 40 GB pagefile |
| GPU          | RTX 3060 Ti or equivalent | RTX 4070 Ti or equivalent |
| Storage Type | SSD | SSD |
| Resolution   | 1920 × 1080 | 1920 × 1080 |

### Space required
| Item | Size |
|---:|---:|
| Installation folder | 333 GB |
| Downloads folder    | 216 GB |
| Total installation  | 550 GB |

</div>


![Installation Guide banner](Images/Installation%20Guide.png)


## Installation Guide (Step-by-step)

### Before you start

- ReaperGleam is a huge modlist. Your PC needs to be ready. Confirm you meet the recommended system requirements and have enough storage space.

### Fixing Pagefile / Memory Crashes

Big Skyrim lists use a lot of virtual memory. If Windows runs out of virtual memory the game will crash even if you have large amounts of physical RAM. You must set a large pagefile.

1. Press Windows + R
2. Type `sysdm.cpl` and press Enter
3. Go to Advanced → Performance → Settings
4. Open the Advanced tab
5. Under Virtual Memory, click Change
6. Turn off “Automatically manage paging file size”
7. Choose the drive Skyrim is installed on
8. Set Custom Size:
   - Minimum: 20480 MB
   - Recommended: 40960 MB
9. Click Set, then OK
10. Restart your PC

**This step is not optional.** Even very large amounts of RAM can fail if Windows refuses to allocate sufficient virtual memory.

### Required software

Install the following before beginning the modlist install:

- Microsoft Visual C++ Redistributables (x64) — download the latest under “Visual Studio 2015–2022”
- .NET Runtime
- Ensure OneDrive is disabled or your modding folders are excluded — OneDrive interferes with Wabbajack installs.

### Accounts you need

- A Nexus Mods account is required. Premium is strongly recommended — without it you'll spend a very long time clicking manual download buttons.

### Folder setup (create on the root of a drive)

Create these folders (example: on C:):

- `C:\ReaperGleam` — installation location for the modlist
- `C:\wabbajack` — where Wabbajack will be installed
- `C:\ReaperGleam_Downloads` — where Wabbajack places downloaded mod files
-    Or
- 'C:\ReaperGleam\Downloads'
- `C:\SkyrimGAME` — a clean Steam library folder for Skyrim

Make sure your antivirus and backup software ignore these folders. If they don't, they may delete or quarantine files Wabbajack needs. If you only have one drive, avoid placing these folders inside `Program Files`.

### Steam setup (before installing Skyrim)

- Disable Steam Overlay
- Set Skyrim’s language to English
- Change updates to “Only update when I launch the game”
- Disable Steam Cloud
- Add a new Steam library pointing to `C:\SkyrimGAME`

If Steam refuses to create another library on the same drive, follow the workaround linked in the original readme.

### Fresh Skyrim install (clean install required)

1. Uninstall Skyrim through Steam
2. Delete leftover files in the old Skyrim folder
3. Delete the following user folders:
   - `%localappdata%\Skyrim Special Edition`
   - `Documents\My Games\Skyrim Special Edition`
4. Reinstall Skyrim into `C:\SkyrimGAME`
5. Launch the game once to allow Creation Club content to install (do not alt-tab during this first launch)
6. Close the game
7. Install the Creation Kit into the same Steam library — this ensures registry entries and base files are correct

### Installing ReaperGleam through Wabbajack

1. Install Wabbajack into `C:\wabbajack`
2. Open Wabbajack and sign in to your Nexus account
3. Select the ReaperGleam modlist
4. Set the following locations in Wabbajack:
   - Installation Location: `C:\ReaperGleam`
   - Download Location: `C:\ResourceDownloads`
5. Start the installation
6. If prompted with “Overwrite”, check it and continue

If anything fails, double-check the previous steps — roughly 99% of issues are caused by missing requirements or Skyrim being installed in the wrong location.

### After installation

- Launch Mod Organizer 2 from inside the `C:\ReaperGleam` folder
- Verify that the control and gamepad settings match the included images
- Start the game from SKSE inside Mod Organizer 2

At this point everything should be ready to play.


![Mod Highlights banner](Images/Mod%20Highlights.png)
<div align="center">

[Complete ModList](Docs/modlist.pdf)

</div>

![Keyboard banner](Images/Keyboard.png)
Skyrim NPC Stats Card
Press your hotkey (default: Y) near an NPC

While in card press hotkey (default: 7) to Flip card for “extra info”

The Dragonborn's Bestiary
To open the new Bestiary menu, press K by default. The hotkey can be changed in the mod's INI file.

Character Menu SE
To open the Character Menu, press N by default. This key can be changed in the INI file.


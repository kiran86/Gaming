# Call of Duty Franchise
Games played by me with links and steps to run them (on linux).

| Title | Year | Platform | Lead developer | Download Link | Installation Steps | Played on Linux |
| --- | --- | --- | --- | --- | --- | --- |
| Call of Duty | 2003 | Windows | Infinity Ward | | Played early version of the game on Windows XP, no installation steps needed. |
| Call of Duty 2 | 2005 | Windows, macOS, X360 | Infinity Ward | | Played early version of the game on Windows XP, no installation steps needed. |
| Call of Duty 3 | 2006 | PS2, PS3, Wii, Xbox, X360 | Treyarch | | Didn't play this game as only available on consoles. |
| Call of Duty 4: Modern Warfare | 2007 | Windows,[b] macOS, PS3, PS4,[b] Wii,[c] X360, XONE[b] | Infinity Ward[b] | | Played early version of the game on Windows XP, no installation steps needed. |
| Call of Duty: World at War | 2008 | Windows, PS3, Wii, X360 | Treyarch | | Played early version of the game on Windows XP, no installation steps needed. |
| Call of Duty: Modern Warfare 2 | 2009 | Windows,[d] macOS, PS3, PS4,[d] X360, XONE[d] | Infinity Ward[d] | | Played early version of the game on Windows 7, no installation steps needed. |
| Call of Duty: Black Ops | 2010 | Windows, macOS, PS3, PS4, PS5, Wii, X360 | Treyarch | | Played early version of the game on Windows, no installation steps needed. |
| Call of Duty: Modern Warfare 3 | 2011 | First Game I played on Linux using Bottles (Begining of Linux Gaming :D) | Infinity Ward, Sledgehammer Games | RELOADED Torrent | <ol><li>Bottle -> Hamburger Menu -> Preferences -> Runner -> Install Proton-GE (latest)</li><li>Create Gaming bottle using Proton-GE as Runner and inside the bottle's details page -> Settings -> Compatibility -> Windows Version -> Windows 7</li><li>Create two separate mount points for both DVD ISOs.<br><pre><code>sudo mkdir -p /mnt/iso<br>sudo mkdir -p /mnt/iso2</code></pre></li><li>Give access to Bottles<br><pre><code>flatpak override --user --filesystem=/mnt/iso com.usebottles.bottles<br>flatpak override --user --filesystem=/mnt/iso2 com.usebottles.bottles</code></pre></li><li>Mount the DVD ISOs in these mount points<br><pre><code>sudo mount -o loop Call.of.Duty.Modern.Warfare.3-RELOADED/rld-mw3a.iso /mnt/iso<br>sudo mount -o loop Call.of.Duty.Modern.Warfare.3-RELOADED/rld-mw3b.iso /mnt/iso2</code></pre></li><li>Now go to the Setting -> Manage Drives in the newly created bottle for the game. Add a new drive with the first iso mount point i. e. /mnt/iso. Say this is D:.</li><li>Save and come back to the details page of the bottle -> Tools -> Command Line. This is the DOS prompt for this bottle. Change drive to D:, and then run Setup.EXE.</li><li>Select C:\Program Files (x86)\ as the installation directory and wait for installer to finish installation from first iso and a popup menu will appear to insert the second dvd.</li><li>Don't close any window. Head back to the bottle's details page - Settings -> Manage Drives as before and now change the same drives path to /mnt/iso2. ** A green tick button should appear. This is little buggy in bottles. The Tick button does not always appear. Change the path with some random characters which makes the button to appear but remember, it is needed to be set on /mnt/iso2. Once done click the ok button of the installation prompt. If the second disk is found, installation will continue and finish.</li><li>From bottle's details page -> Legacy Wine Tools -> Explorer, copy contents of the Crack folder from the second iso mount drive and paste into the game installation main directory.</li><li>From the main installation directory run the game exe, and it will run like a charm.</li></ol> | 20-09-2026 |
| Call of Duty: Black Ops II | 2012 | Ubuntu 26.04 + Lutris | Treyarch | RELOADED Torrent | No special tinkering needed. Mounted the iso and ran the setup.exe from Lutris. Lutris taken care of the rest. Copied the crack files over the installation directory. | 20-09-2026 |
| Call of Duty: Ghosts | 2013 | Windows, PS3, PS4, Wii U, X360, XONE | Infinity Ward |
| Call of Duty: Advanced Warfare | 2014 | Windows, PS3, PS4, X360, XONE | Sledgehammer Games |
| Call of Duty: Black Ops III | 2015 | Windows, macOS, PS3, PS4, X360, XONE | Treyarch |
| Call of Duty: Infinite Warfare | 2016 | Windows, PS4, XONE | Infinity Ward |
| Call of Duty: WWII | 2017 | Windows, PS4, XONE | Sledgehammer Games |
| Call of Duty: Black Ops 4 | 2018 | Windows, PS4, XONE | Treyarch |
| Call of Duty: Modern Warfare | 2019 | Windows, PS4, XONE | Infinity Ward |
| Call of Duty: Black Ops Cold War | 2020 | Windows, PS4, PS5, XONE, X|S | Treyarch, Raven Software |
| Call of Duty: Vanguard | 2021 | Windows, PS4, PS5, XONE, X|S | Sledgehammer Games |
| Call of Duty: Modern Warfare II | 2022 | Windows, PS4, PS5, XONE, X|S | Infinity Ward |
| Call of Duty: Modern Warfare III | 2023 | Windows, PS4, PS5, XONE, X|S | Sledgehammer Games |
| Call of Duty: Black Ops 6 | 2024 | Windows, PS4, PS5, XONE, X|S | Treyarch, Raven Software |
| Call of Duty: Black Ops 7 | 2025 | Windows, PS4, PS5, XONE, X|S | Treyarch, Raven Software |
| Call of Duty: Modern Warfare 4 | 2026 | Windows, PS5, X|S, NS2 | Infinity Ward |
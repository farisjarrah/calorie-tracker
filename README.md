# calorie-tracker
Dead simple calorie tracker, saves data locally/personal icloud. No ads, no tracking. Single html page. For people that dont need fancy features or that dont want to download an app just to do basic things.

## Usage:
Hosted on github pages: https://farisjarrah.github.io/calorie-tracker/
Or just save and open the index.html in a your browser locally.
Even on github pages, no data is transmitted anywhere and you are only opening up your data json file from local/cloud storage of your choice.


If you save your file to icloud storage you can use the same file for all of your devices, probably works with any other filesystem integration type too, but untested.

### Saving on iPhone/iPad (iOS Safari)
Tap **Save file** and choose **Save to Files**. iOS Safari can't overwrite the file you opened, so treat the save as a *backup copy*: if iOS offers it, pick **Replace** to keep a single file; if it saves a new file instead (e.g. `calorie-data.json 2`), that's fine too — once you have a backup, you can delete the older duplicate.

**You can't lose progress either way.** As you track, the app auto-saves your latest session on the device (in the browser's storage). If you refresh, close the tab, or come back later, it just picks up where you left off — the last session loads automatically, no prompts. The file you save to iCloud is your cross-device backup. To make a file show up in the Files picker, open it once in the Files app so iCloud downloads it, then always pick **Browse → iCloud Drive**, not "Recents".

The **☰ menu** (top right) has: **Save backup file…** (download the JSON to iCloud), **Restore last session** (reload the on-device autosave), **Open a data file…** (load a different JSON, e.g. one saved on another device), and **New file**.

### Install as an app (PWA)
Works as a normal website, or install it to your home screen for a full app experience:
- **iPhone/iPad:** Share button → **Add to Home Screen**.
- **Android:** Chrome menu (⋮) → **Add to Home screen** or **Install app**.
- **Desktop:** install icon in the Chrome/Edge address bar (or menu → **Install...**).
The installed app opens full-screen with its own icon; the data flow (open JSON + auto-save + save to iCloud) is unchanged.

## WARNING:
This was vibecoded using the free OpenCode Big Pickle AI Model 08/2026.

## Credits
Icon: "Green Apple Icon" by IconArchive.com, from Wikimedia Commons (CC0 / public domain).

## Screenshots
<img width="773" height="888" alt="image" src="https://github.com/user-attachments/assets/2f1362e2-3dcf-4bfd-ac71-f702db46ea68" />
<img width="763" height="638" alt="image" src="https://github.com/user-attachments/assets/06527d85-be16-4144-9d25-1dba479d6b81" />
<img width="768" height="948" alt="image" src="https://github.com/user-attachments/assets/f57d3d93-a637-4e31-990b-db57aa8a8916" />
<img width="764" height="962" alt="image" src="https://github.com/user-attachments/assets/3a7286a1-75c3-40e4-9059-e33a4d3e565d" />

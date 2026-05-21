<img width="2778" height="1940" alt="image" src="https://github.com/user-attachments/assets/cbcb8a8a-30e1-4b55-8b1a-599a514b82cd" />


# D&D Character Sheet Web-App

Welcome to my little project. 
This is a DND character sheet web-app that automatically saves any changes you enter between sessions locally on your device.

## Features
- **Persistent Local Storage**: Every stat, note, and checkmark is saved automatically to your browser's `localStorage` as you edit.
- **Character Portraits**: Support for local image uploads that stay with your sheet even after a refresh.
- **Interactive Tooltips**: Dynamic descriptions for attributes, skills, and mechanics with.
- **Multi-Page Layout**: Dedicated views for combat stats and spellcasting.

## How it Works
The app is built entirely with HTML, CSS, and Vanilla JavaScript. It requires no server or database. Because it uses `localStorage`, your data is unique to the browser and device you use to open the file.

## Tablet & Web-App Use
This project is designed to work smoothly on tablets. For the best experience, it is recommended to save the page to your device's springboard as a web-app. On iPad, this **must** be done using **Safari** if you don't want web browser UI elements (tap the Share icon and select **"Add to Home Screen"**); Android requirements may vary depending on the browser and device used and I have no android tablet to test this.

## Manually Saving and Restoring Data
If you want to move your character to a different device, or a different browser (e.g., from Chrome to Firefox), you can use the built-in Backup system:

### To Save/Export:
1. Click the **"Backup Text"** button at the bottom of the page.
2. A prompt will appear containing a long string of encoded text.
3. Copy this text and save it somewhere safe (like a notepad or a message to yourself).

### To Restore/Import:
1. Open the app on the new device or browser.
2. Click the **"Restore Text"** button.
3. Paste your backup code into the prompt and click OK. 
4. Your character's stats, inventory, and notes will be instantly updated.

---
*Please note: The themes function is currently in early development.*

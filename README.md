# ActiveTab Watcher

**ActiveTab Watcher** is a Chrome/Chromium extension that tracks the active time spent on browser tabs. It records how much time is spent on each website and displays a visual summary for the user.  

---

## Features

- Tracks the currently active browser tab.  
- Records time spent on each website in seconds.  
- Displays time using both text and visual bars in a clean popup.  
- Stores data locally using Chrome Storage.  
- Easy access via the extension icon.  

---

## Installation

1. Clone or download this repository.  
2. Open Chrome or Chromium browser.  
3. Navigate to `chrome://extensions/`.  
4. Enable **Developer Mode**.  
5. Click **Load unpacked** and select your extension folder.  

---

## File Structure

```

/ActiveTab Watcher
├─ manifest.json       # Extension configuration
├─ popup.html          # Popup UI
├─ style.css           # Popup styles
├─ popup.js            # Popup script
├─ watcher.js          # Background tab tracking logic
└─ icon.png            # Extension icon

```

---

## Usage

1. Install the extension.  
2. Click the extension icon in the toolbar.  
3. View the active time spent on each tab/website.  
4. Data is saved automatically and persists across sessions.  

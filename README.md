# 📦 VisualDrive

**A blazing-fast, non-admin treemap visualizer for your folders and drives!**

Made with ❤️ using Python + Pygame, this tool lets you scan any folder or drive and instantly see where your storage is going — all without needing admin access. It’s a portable `.exe` that just *works*.

---

## 🪄 Features

* 🔍 **Instant folder size visualizer**
* 📊 **Treemap-style view of files and folders**
* 🧠 **File type breakdown with pie chart**
* 🧱 **Zoom + Pan support**
* 💾 **Total scanned size bar**
* 😎 **Runs WITHOUT admin rights**
* 🧁 **Clean UI, no terminal window, just double-click and go**

---

## 🚀 How To Run It

> **IMPORTANT:** You do *not* need to install Python or have admin permissions. It’s pre-packaged!

### 1. ✅ Download `visualdrive.exe`

* Get it from the [Releases](https://github.com/MicahThePro/Visual-File-Manager/releases) section of this repo

### 2. 🖱 Just Double-Click

* Yup. That’s it. No installs. No console windows. Just GUI magic.

### 3. 📂 Choose Folder or Drive

* When it opens, it’ll ask if you want to scan a `Drive` or a `Folder`

  * Type `D` for Drive (like `C:`)
  * Type `F` for Folder and pick one

### 4. 🔍 Watch it scan & visualize

* Progress bar at the bottom
* Treemap view shows folder/file sizes
* File types are shown in a pie chart (top-right)
* Total visualized size shown at the bottom bar

### 5. 🖱 Controls

| Action          | How                            |
| --------------- | ------------------------------ |
| Zoom In         | Scroll Up                      |
| Zoom Out        | Scroll Down                    |
| Pan / Drag View | Click and Drag with Left Mouse |
| Refresh Scan    | Press `R`                      |

---

## 🧠 Tech Stack

* `Python 3.9+`
* `pygame`
* `squarify`
* `tkinter`

---

## 🧪 Want to Build It Yourself?

Clone this repo and run:

```bash
pip install pygame squarify
pyinstaller --onefile --noconsole wiztree_clone.py
```

---

## 🛡 License

MIT — Use it, modify it, remix it!

---

## 🤖 Made by Micah

> 12 y/o coder. Gen Z. Built different. Harvard-bound.

If you like this project, star it, remix it, or show it off on social media with a shoutout!

---

### 🔗 [micahswebsite.xyz](http://micahswebsite.xyz)

# 📋 Clipboard History

Clipboard manager for GNOME

<img src="./screenshot.png" alt="A screenshot of the clipboard manager, showing clipboard history including images" width="400">
---

## 🧰 Features:

- Highly customizable
- Supports both text and images
- Allows pinning items to top
- Includes a "private" mode
- Has configurable shortcuts
- Keyboard control

### In-Menu Keyboard Controls

- Use arrows to navigate
- `v` to paste directly from menu
- `p` to pin item
- `<Delete>` to delete an item

---

## ✅ GNOME Version Support

Depending on your GNOME version, you will need to install the following Clipboard Indicator versions:

- **GNOME 46 and above:**
  - Use latest version
- **GNOME 45:**
  - v57
- **GNOME 42-44:**
  - v47
- **GNOME 40-41:**
  - v39
- **GNOME <40:**
  - v37

---

## ⌨️ Contributing

Contributions to this project are welcome. Describe your changes in the pull request (I am happy to have unsolicited PRs).

My goal is to maintain this project as a fork (of [Tudmotu's](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator/blob/master/extension.js)) that allows contributions more easily than the original project. I will try to keep the project up-to-date with the original project.

After implementing a change to the javascript code, type the following to preview the changes: 
```
make all
make install
make nested-session
```

If the changes are related to the schema, type the following into the terminal to log out of your account and restart wayland so that you can preview the changes:
```
make all
make install
gnome-session-quit --logout --no-prompt
```

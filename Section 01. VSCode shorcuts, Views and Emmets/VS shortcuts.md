# 1. Breadcrumb, minimap, zen mode

## 1. Minimize Breadcrumbs:
```diff
- Using the Command Palette
  ```
Press `Ctrl + Shift + P`(or `Cmd + Shift + P` on Mac) to open the Command Palette.
Type "Toggle Breadcrumbs" and select it. This will hide or show the breadcrumbs.

```diff
+ Using Settings:
  ```
Open the Settings by going to File > Preferences > Settings (or `press Ctrl + ,` on Windows/Linux, or `Cmd + , on Mac`).
In the search bar, type `"breadcrumbs"`.
Look for the option "Breadcrumbs: Enabled" and uncheck it to hide the breadcrumbs.

```diff
! Details:
  ```
Breadcrumbs show the file structure and symbols (like functions, classes, etc.) in your current file at the top of the editor. 
If you disable it, that area will no longer display this information, giving you a cleaner view of your code.

## 2. Minimize Minimap:
```diff
- Using the Command Palette
  ```
Press Ctrl + Shift + P (or Cmd + Shift + P on Mac) to open the Command Palette.
Type "View: Toggle Minimap" and select it. This will hide or show the minimap.

```diff
+ Using Settings:
  ```
Open the Settings by going to File > Preferences > Settings (or press Ctrl + , on Windows/Linux, or Cmd + , on Mac).
In the search bar, type "minimap".
Look for the option "Editor: Minimap Enabled" and uncheck it to disable the minimap.

```diff
! Settings in JSON (optional advanced):
  ```
You can also directly edit your settings file by going to File > Preferences > Settings and clicking the {} icon in the top right corner to open the settings in JSON format.

## 3. Zen Mode:
```diff
! Using Keyboard Shortcut:
  ```
Windows/Linux: Press Ctrl + K then Z.
Mac: Press Cmd + K then Z.
```diff
- Exiting Zen Mode:
  ```
Press Escape twice to exit Zen Mode.

# 2. HTML Emmet Abbreviations

```diff
- Creating Nested Elements
  ```
Abbreviation: ul>li*5

```diff
+ Creating an Element with ID and Class
  ```
Abbreviation: div#container.main

```diff
! Adding Text Content
  ```
Abbreviation: h1{Welcome to Emmet}

```diff
- Creating Multiple Items with Numbering
  ```
Abbreviation: h2.item$*3

```diff
- Table Structure
  ```
Abbreviation: table>tr*3>td*2



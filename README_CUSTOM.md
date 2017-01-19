Custom jQuery Build for FigPii Tracker
======================================

This is custom build jQuery version to use with FigPii tracker scripts. Based on *1.12-stable* branch.

Global variables like **$** and **jQuery** removed and **_FJQ** global variable added to prevent conflict.

All tracking scripts must use **_FJQ** suffix instead of **$** or **jQuery**.

Example: `_FJQ('a.menu').addClass('active');`

To save file size and reduce initialization overhead following modules are striped from this build:

- wrap
- offset
- event/alias
- effects
- deprecated
- ajax/jsonp
- ajax/script

How to Build
============

Execute the following.

1) npm install
2) npm run buildCustom

Check **dist** folder.
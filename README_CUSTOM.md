Custom jQuery Build for FigPii Tracker
======================================

This is custom build jQuery version to use with FigPii tracker scripts.

Global variables like **$** and **jQuery** removed and **_FJQ** global variable added to prevent conflict.

AMD variable changed from ***jquery*** to ***fjq***.

All tracking scripts must use **_FJQ** suffix instead of **$** or **jQuery**.

Example: `_FJQ('a.menu').addClass('active');`

How to Build
============

Execute the following.

1) npm install
2) npm run buildCustom

Check **dist** folder.
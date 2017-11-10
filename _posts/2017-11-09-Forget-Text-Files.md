---
layout: post
title: Save and Retrive Text Using Toolbox
image: /img/drag-and-drop-clipboard.png
tags: [Visual Studio, Copy, Paste, Drag And Drop Clipboard, Toolbox]
---


In my [last post](/2017-11-03-Clipboard-Ring), I showed you how we can use __Clipboard Ring__ in Visual Stiudio or SSMS to copy and paste multiple items more efficiently. Clipboard ring is great but what if you do not know when you will need the text back? Or what if you simply do not want to cycle through <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>V</kbd> again and again. Sure we can use text files, but its a lot of work to open a text editor and go back and forth between two applications.

__We Can Do Better__

Highlight the text you want to save and drag and drop it to toolbox panel. (If you do not see your Toolbox Panel, goto view > toolbox. Or simply use <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>X</kbd>.) Then whenever you need it, just drag the text back to wherever you want. 


![alt text][Demo]

Unfortunately, unlike __Clipboard Ring__ this is only available in Visual Studio. SQL Server Management Studio gets no love. 


[Demo]: /img/DragDropClipboard.gif "Clipboard Ring Demo"

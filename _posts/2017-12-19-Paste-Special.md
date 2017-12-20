---
layout: post
title: Visual Studio, Paste Special
image: /img/json-xml.png
tags: [Visual Studio, Copy, Paste, Paste Special, Toolbox]
---


XML and JSON are basic bread and butter of data transfer in modern programming languages. If you have worked with these formats, you must have spent some time writing classes to serialize or deserialize them. If so, this small trick will come in handy. Visual Studio has inbuilt tool to generate classes from json or xml string. 

__Paste Special__

Simply copy your json or xml string to your clipboard and then select Edit > Paste Special > Paste JSON as Classes or Paste XML as Classes. You can also use keyboard shortcut <kbd>ALT</kbd> + <kbd>E</kbd>, <kbd>S</kbd>, <kbd>J</kbd> for json or <kbd>ALT</kbd> + <kbd>E</kbd>, <kbd>S</kbd>, <kbd>S</kbd> for xml. This tool has been available for quite few versions of visual studio, however some earlier release of vs2017 did not include paste special option under Edit menu. If you cannot find this under your edit menu, upgrade your visual studio or use some online tool like [this one](http://xmltocsharp.azurewebsites.net/) for xml and [this one](http://json2csharp.com/) for json.


![alt text][Demo]

This tool can also generate vb.net classes. Just use paste special in a file with .vb extension. 


[Demo]: /img/ReadXmlAndJson3.gif "Paste Special"

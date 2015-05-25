
***
Welcome to the LeagueSharp.Documentation wiki!


Hello L# community! 
This will be your basic "Getting started" tutorial.

### Getting Started:
## 1.Downloading Visual Studio
For this we will want to navigate [https://www.visualstudio.com/en-us/downloads/download-visual-studio-vs.aspx](Here) and scroll down till we will see: "Community 2013 with Update 4" 
You may download an express version, but this will result in "Resharper" not being compatible with this version.

Next thing you will want to do is install. 
The installation may take up to 1 Hour, so please be patient :+1: 

After the installation is done you may be confused as to the installation path (i know i was)
For me it was: C:\Visual studio community 2013
But if you still did not manage to find it please navigate to Start->Search for Visual Studio->There you go :)

Now that we are done with the download we can start making our first project! which takes us to the second topic.

## 2.Creating C# Project
You have Visual Studio installed and you are ready to kick things up and start your first project! for this you may want to create a C# project.

**For this please follow the image instructions : **
![Open Visual studio](http://puu.sh/hZXKE/b27bbe9cc1.png)

Next thing you will be greeted with:
![](http://puu.sh/hZXSM/926feb518b.png)

You will want to hit the "New project" button and select the following:

Installed->Template->Visual C#->Windows Desktop->Console Application
![](http://puu.sh/hZY0L/f7ef0ddc2f.png)

Hit Ok and you are good to go! 

## 3.Adding References to C#

To start making assemblies for Leaguesharp, will want to add relevant References.
What are references you ask?

To add the references you need go to:

![](http://puu.sh/hZYh1/3a91988ad3.png)

Click Add reference:

![](http://puu.sh/hZYiO/b4331f8418.png)

Navigate to Browse:

![](http://puu.sh/hZYlK/36fac31d45.png)

Now, to add your needed refrences click Browse, and navigate to your L# folder(C:\LeagueSharp\System):

![](http://puu.sh/hZYs6/0a09c93d23.png)
The needed .dlls are the one who are marked.

Click Add and then tick the boxes and click Ok:

![](http://puu.sh/hZYuu/9a668a1f90.png)

If we are interested in adding Drawings to our assembly navigate to "Assemblies"->Find System.Drawing and tick it:


![](http://puu.sh/hZYyd/2a97a325eb.png)

After that we will want to this lines on the top of the project:

* using LeagueSharp;
* using LeagueSharp.Common;
* using LeagueSharp.Common.Data;
* using Color = System.Drawing.Color;
* using SharpDX;

![](http://puu.sh/hZYEz/74f5d4975a.png)


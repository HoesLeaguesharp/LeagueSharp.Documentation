### 3.Adding References to C#

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

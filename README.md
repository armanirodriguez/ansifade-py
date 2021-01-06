# ANSIFade
**Easily create fade gradiants using ASNI color codes**<br>
ANSIfade requires Python 3.x and uses no external modules. <br>Easily create
beautiful looking commandline graphics that can be viewed on any terminal
supporting ANSI.

![Example Image](https://i.imgur.com/OFpyCMV.png)

**Installation**<br>
git clone https://github.com/armanirodriguez/ansifade<br>
cd ansifade<br>
chmod +x ansifade.py<br>

**Usage**<br>
./ansifade.py <file.txt> \<color1> \<color2> <br>
<br>
color1 designates left side of the gradiant and color2 designates the right<br>

Colors can be specified by name or rgb value<br>
Ex: <br>
./ansifade.py data.txt red yellow<br>
or<br>
./ansifade.py data.txt 252,8,8 255,202,0<br>
or<br>
./ansifade.py data.txt red 255,202,0<br>

<br>
Available colors: pink,purple,blue,cyan,turquoise,lime,green,white,grey,red,yellow<br>


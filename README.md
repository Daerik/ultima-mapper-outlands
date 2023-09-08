# Outlands Mapper

Video guide:
http://ultimamapper.com/outlands_mapper.webm OR https://www.youtube.com/watch?v=uzhyJN-Woqs

Step by step:
1) Download & Install Ultima Mapper from http://www.ultimamapper.com

2) Download & Extract the files contained in this GitHub to C:\Users\USER\Documents\outlandsmapper-master

3) Run Ultima Mapper

4) Go File > Settings

5) Set the Resource Path to the new folder you just created:  C:\Users\USER\Documents\outlandsmapper-master

6) Restart Ultima Mapper

To see the Outlands map go View > Current Facet > Felucca

To see the Outlands markers go Markers > Select



---------------------------------------------------------

EXAMPLE MARKER FILE:

```
<?xml version="1.0" encoding="UTF-8"?><Pack Name="Bodies of Water" Revision="0">

<Marker Name="Example Body Of Water" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>

</Pack>
```

The easiest way I have found to edit them and keep the formating as well as making it easier to collaborate would be to edit the marker file itself rather than adding it using mapper, for example if i wanted to add an additional marker it would then look like this

```
<?xml version="1.0" encoding="UTF-8"?><Pack Name="Bodies of Water" Revision="0">

<Marker Name="Example Body Of Water" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>
<Marker Name="Example Body Of Water 2" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>

</Pack>
```

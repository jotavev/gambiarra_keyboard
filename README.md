# Gambiarra keyboard layout 

Gambiarra is a abnt2 brazilian keyboard layout with some mods.

![alt text](https://github.com/jotavev/gambiarra_keyboard/blob/1164500244b2b2b1e38e5b4e1f4d87dfc0ed388f/gambiarra.png)

this is not a final version, but...
___
### Install
```
$ cd
$ git clone https://github.com/jotavev/gambiarra_keyboard/
$ cd gambiarra_keyboard/
$ sudo cp jotav /usr/share/X11/xkb/symbols/
```
Add the new layout declaration to ```/usr/share/X11/xkb/rules/evdev.xml```
```
...
    <layout>
      <configItem>
        <name>jotav</name>

        <shortDescription>jv</shortDescription>
        <description>abnt2_gambiarra</description>
        <languageList>
          <iso639Id>por</iso639Id>
        </languageList>
      </configItem>
      <variantList>
      </variantList>
    </layout>
...

```
inside a &lt;layoutList&gt; ... &lt;/layoutList&gt;

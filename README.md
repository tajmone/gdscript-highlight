GDScript Highlight
==================

    GDScript    v1.0
    Godot Theme v1.0

GDScript language definition and theme for André Simon’s **Highlight** tool:

-   <http://www.andre-simon.de/>

By [Tristano Ajmone](https://github.com/tajmone/) (2017/02/16). Released under the public domain according to the [Unlicense](./LICENSE) license terms.

Project home:

-   <https://github.com/tajmone/gdscript-highlight>

Introduction
============

This repository contains the GDScript language definition file for **Highlight** tool, plus a theme mimicking Godot’s native editor default theme:

-   `gdscript.lang` — The GDScript lang definition file.
-   `edit-godot.theme` — Godot Theme.

Manual Setup
============

Manual setup is only required while waiting for GDScript to become part of **Highlight**’s official bundle.

    Highlight/langDefs/gdscript.lang   <= copy file to here
    Highlight/themes/edit-godot.theme  <= copy file to here
    Highlight/filetypes.conf           <= edit file 

Copy “`gdscript.lang`” in Highlight’s “`langDefs`” folder, and “`edit-godot.theme`” in the “`themes`” folder.

Open **Highlight**’s “`filetypes.conf`” file in a text editor and add the following line somewhere before the closing bracket (`}`) at the end of the file:

     { Lang="gdscript", Extensions={"gd"} },

… this will associate the “`*.gd`” file extension with GDScript syntax. For more info, see:

-   <http://www.andre-simon.de/doku/highlight/en/highlight.php#ch3_7>


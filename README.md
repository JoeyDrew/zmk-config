# Split38 zmk-config
A 38-key split keyboard built around Nice!Nano boards.

Split38's KiCad project is archived [here](https://github.com/JoeyDrew/split38).

Current keymap:

Inspired by [Taipo](https://inkeys.wiki/en/keymaps/taipo), this map has a Colemak mod-dh base layer alongside a momentary *or* togglable chorded layer.

_subject to change_

Here's a rough draft diagram for the chords (all inputs shown are left handed - right hand inputs are mirrored):

base:
| r   | s   | n   | i   | tab  |
| --- | --- | --- | --- | ---- |
| a   | o   | t   | e   | ent  |
| 8   | 4   | 2   | 1   | esc  |
| ctl |     | alt | spc | shft |

| l        | ⚪⚪⚪⚪<br>⚫⚫⚪⚪         | g     | ⚫⚫⚪⚪<br>⚪⚪⚪⚪         |
| -------- | -------------------- | ----- | -------------------- |
| u        | ⚪⚪⚪⚪<br>⚪⚫⚫⚪         | p     | ⚪⚫⚫⚪<br>⚪⚪⚪⚪         |
| h        | ⚪⚪⚪⚪<br>⚪⚪⚫⚫         | y     | ⚪⚪⚫⚫<br>⚪⚪⚪⚪         |
| f        | ⚪⚪⚪⚪<br>⚫⚪⚫⚪         | j     | ⚫⚪⚫⚪<br>⚪⚪⚪⚪         |
| c        | ⚪⚪⚪⚪<br>⚪⚫⚪⚫         | v     | ⚪⚫⚪⚫<br>⚪⚪⚪⚪         |
| d        | ⚪⚪⚪⚪<br>⚫⚪⚪⚫         | w     | ⚫⚪⚪⚫ <br>⚪⚪⚪⚪        |
| k        | ⚪⚪⚪⚪  <br>⚫⚫⚫⚪       | x     | ⚫⚫⚫⚪ <br>⚪⚪⚪⚪        |
| m        | ⚪⚪⚪⚪<br>⚪⚫⚫⚫         | b     | ⚪⚫⚫⚫<br>⚪⚪⚪⚪         |
| q        | ⚪⚪⚪⚪<br>⚫⚪⚫⚫         | z     | ⚫⚪⚫⚫<br>⚪⚪⚪⚪         |
| [        | ⚪⚪⚪⚪<br>⚪⚫⚪⚪<br>⚫⚪⚪⚪ | ]     | ⚪⚪⚪⚪<br>⚫⚪⚪⚪<br>⚪⚫⚪⚪ |
| {        | ⚪⚪⚪⚪<br>⚪⚪⚫⚪<br>⚪⚫⚪⚪ | }     | ⚪⚪⚪⚪<br>⚪⚫⚪⚪<br>⚪⚪⚫⚪ |
| <        | ⚪⚪⚪⚪<br>⚪⚪⚪⚫<br>⚪⚪⚫⚪ | >     | ⚪⚪⚪⚪<br>⚪⚪⚫⚪<br>⚪⚪⚪⚫ |
| \        | ⚪⚫⚪⚪<br>⚪⚪⚫⚪<br>⚪⚪⚪⚪ | \|    | ⚪⚪⚫⚪<br>⚪⚫⚪⚪<br>⚪⚪⚪⚪ |
| -        | ⚪⚫⚪⚪<br>⚪⚪⚪⚫<br>⚪⚪⚪⚪ | _     | ⚪⚫⚫⚪<br>⚪⚪⚪⚫<br>⚪⚪⚪⚪ |
| =        | ⚪⚪⚪⚪<br>⚪⚫⚪⚪<br>⚪⚪⚪⚫ | +     | ⚪⚪⚪⚪<br>⚪⚫⚫⚪<br>⚪⚪⚪⚫ |
| ,        | ⚪⚪⚫⚪<br>⚪⚪⚪⚫<br>⚪⚪⚪⚪ | .     | ⚪⚪⚪⚫<br>⚫⚪⚪⚪<br>⚪⚪⚪⚪ |
| /        | ⚪⚪⚫⚪<br>⚫⚪⚪⚪<br>⚪⚪⚪⚪ | ?     | ⚪⚪⚪⚫<br>⚪⚪⚫⚪<br>⚪⚪⚪⚪ |
| `        | ⚪⚪⚪⚪<br>⚪⚪⚪⚫<br>⚫⚪⚪⚪ | ~     | ⚪⚪⚪⚪<br>⚪⚪⚪⚫<br>⚪⚫⚪⚪ |
| '        | ⚪⚫⚪⚪<br>⚫⚪⚪⚪<br>⚪⚪⚪⚪ | "     | ⚪⚫⚫⚪<br>⚫⚪⚪⚪<br>⚪⚪⚪⚪ |
| ;        | ⚪⚪⚪⚪<br>⚫⚪⚪⚪<br>⚪⚪⚫⚪ | :     | ⚪⚪⚪⚪<br>⚪⚪⚫⚪<br>⚫⚪⚪⚪ |
|          |                      | gui   | ⚪⚪⚫⚪<br>⚪⚫⚪⚫         |

numbers are accessed from the third row, `8 4 2 1`, and odd numbers are achieved by adding inputs together. for example, `5`'s input is `4 1 `. 

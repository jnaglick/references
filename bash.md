# <a name="top"></a>bash

1. [keyboard shortcuts](#keyboard-shortcuts)
2. [special variables](#special-variables)
3. [autocomplete](#autocomplete)
4. [builtins](#builtins)

---


#### <a name="keyboard-shortcuts"></a> keyboard shortcuts [\^](#top)

###### cool
|seq            |action
|---            |---
|^ r            | search history 
|esc+. (period) | insert last arg from previous command

###### move cursor

|seq            |action           |etc
|---            |---              |---
|^ a            |move to start of line
|^ e            |move to end of line
|esc+f          |move forward one word | use .inputrc for ^-sequences, terminal emulator mapping for alt
|esc+b          |move backward one word| ditto above


###### edit
|seq          |action           |etc
|---          |---              |---
|^ w          |cut word before cursor
|^ u          |cut line before cursor | mnemonic: 'u'ndo this stuff
|^ k          |cut line after cursor | mnemonic: 'k'ill that stuff
|^ y          |paste            |mnemonic: opposite of 'y'ank

#### <a name="special-variables"></a>  special variables [\^](#top)

|var          |meaning
|---          |---
|!!           |prev command
|!$           |last arg from previous command


#### <a name="autocomplete"></a> autocomplete [\^](#top)

|symbol         |meaning
|---            |---
| ~ (tilde)     |user name
| @ (at sign)   |machine name
| $ (dollar)    | env variable


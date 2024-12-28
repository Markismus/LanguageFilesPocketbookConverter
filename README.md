# Language files for Pocketbook Dictionary Converter
Pocketbook has binary dicionary dic-files, that can be created from xdxf-files with the a windows program _converter.exe_ and a set of three language files: keyboard.txt, collates.txt and morphems.txt
The file _converter.exe_ is a patch binary to remove the maximum block count. (See [this post on mobileread.](https://www.mobileread.com/forums/showthread.php?p=3923282#post3923282) ) This allows for a easier conversion form xdxf- to dic-format.

**Comparing language folders**
_These language folders are present:_
- cs
- da
- de
- el
- en
- eng
- es
- fr
- fre
- he
- heb
- hu
- is
- it
- ita
- jaK
- jaR
- kk
- la
- lt
- lv
- nl
- no
- pl
- pt
- ro
- ru
- rus
- sk
- sl
- sp
- spa
- sv
- tr
- uk
- ukr

( Explanantions of the language a folder refers to is usually given in the first line of keyboard.txt )

_en/collates.txt  is different from:_
- fre
- heb
- he
- ita
- jaK
- jaR
- pl
- ro

_en/keyboard.txt is different from:_
- cs
- da
- de
- el
- eng     ( en is more expanded)
- es
- fre
- fr      ( Start like eng, but misses last 8 lines)
- heb
- he
- hu
- is
- ita     ( Italian, misses numbers and symbols, uses accented vowels.)
- it      ( Italian, misses accented vowels)
- jaK
- jaR     ( States English keyboard, but misses numbers and most symbols)
- kk      ( Kazakh)
- la
- lt      ( Lituanian)
- lv      ( Latvian)
- nl      ( Identical to DE)
- no      ( Norvegian)
- pl
- pt
- ro      ( Romanian, Qerty, accented letters, no numbers, no symbols)
- ru
- rus     ( Both ru and rus state Russian
- sk      ( slovak)
- sl      ( Slovene)
- spa     ( Start like eng, but misses last 8 lines)
- sp      ( States ES: Spanish )
- sv
- tr      ( Turkish)
- uk      ( UA Ukrainian, uk is more expanded than ukr)
- ukr     ( UA Ukrainian, ukr makes a difference between lc and uc  of a few symbols )

_en/morphems.txt is different from:_
- de
- fre     ( Identical to fr)
- fr      ( Identical to fre)
- heb     ( Identical to he)
- he      ( Identical to heb)
- ita
- jaK
- jaR
- nl      ( Identical to de)
- ro      ( Identical to de)
- ru      ( Identical to ru)
- rus     ( Identical to rus)
- spa
- sv
- uk      ( Identical to ukr)
- ukr     ( Identical to uk)

_Conclusion:_
- nl is copied from de

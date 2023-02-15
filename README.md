# Element-Word-Maker
This script will find out if a word can be spelled out using element abbreviations from the periodic table
<br>
<br>
SUMMER PROJECT

## languages
- python (cuz python roolz)

## how to do it (options; code all)
- get first two letters of prompt. check array based on number first letter is in alphabet. if entry equals the first two letters, use that. otherwise, use first letter, then look at next two after one or two depending on if two letters satisfies or only one.
- go through each abbrv group by first letter, then if no letters satisfy try different first letter (if indium in doesnt work for entire prompt, start over at index and try i
  - have condition saying if previous abbrv was two words, and new abbrv is one word, next abbrv HAS to be two words since having i then n instead of in is usless, have i then ni 
- dont care about spaces (do entire prompt as one; when word ends and new begins, one element abbrv can satisfy both [hell raiser <-- end of hell and start of raiser can be substituted with lawrencium lr])
- care about spaces (do each word individually; less options and configurations, but faster)
- use fictional elements (since periodic table does not cover all of alphabet)
- random integer for groups with letter (would work better with fictional since there arent a lot of options with real elements)

## sources
- http://www.lmntology.com/nameAsElementsWhite.php
- https://dailyinfographic.com/the-periodic-table-of-fictional-elements

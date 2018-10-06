## Info

Repeat a word or a sentence X times, everything being user-supplied.

## Code

``{source:repeat}{set:number|{isnumber:{input:1}}}{set:input|{input:2|9999}}{set:text|{if:{get:number|1}|{if:{get:number|1}>0|{if:{input:2}|{repeat:{get:number|1}|{if:{get:input}|{get:input} }}|}|}|}}{if:{get:text|4}|{get:text|4}|Usage: `repeat <amount> <text>`}``

## Example

`!repeat`

Usage: `repeat <amount> <text>`

————————————————————

`!repeat 10 meep`

meep meep meep meep meep meep meep meep meep meep

## Credits

Created by Xenthys#0001  

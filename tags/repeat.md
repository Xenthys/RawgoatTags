## Info

Repeat a word or a sentence X times, everything being user-supplied.

## Code

``{set:number|{isnumber:{input:1}}}{set:input|{input:2|9999}}{set:text|{if:{get:number|1}|{if:{get:number|1}>0|{if:{input:2}|{repeat:{get:number|1}|{if:{get:input}|{get:input} }}|}|}|}}{if:{get:text|4}|{get:text|4}|Usage: `repeat <amount> <text>`}``

## Example

Input: `!repeat`  
Output: ``Usage: `repeat <amount> <text>` ``

Input: `!repeat 10 meep`  
Output: `meep meep meep meep meep meep meep meep meep meep`

Created by Xenthys#0001

# Simple Calculator

## Description

Unveil PHP Secrets.

http://45.129.40.107:9668/ 

## Attachments

[simple_calculator_updated.zip](https://ctf.l3ak.team/files/0ddfdb251672ce7e8fce99784fa624fe/simple_calculator_updated.zip?token=eyJ1c2VyX2lkIjoxNDQsInRlYW1faWQiOjYxLCJmaWxlX2lkIjo4OH0.ZlOY8Q.j_H4sGwdzH_mVkS5Es-tN15EtUs)

## Solution (Unfinished)

It seems like the intended solution is to exploit the use of
<code>eval()</code> in the PHP script (see Attachments) in order to do some remote code execution. However, there is a regex
check for alphabetic characters and quotes before <code>eval()</code> is called. I'm not sure how to
execute any meaningful command with these constraints.

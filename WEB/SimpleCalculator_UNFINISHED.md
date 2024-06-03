# Simple calculator

## Description

Unveil PHP Secrets.

[Build](https://github.com/L3AK-TEAM/L3akCTF-2024-public/tree/main/web/simple_calculator/build)

## Attachments

[simple_calculator_updated.zip](https://github.com/L3AK-TEAM/L3akCTF-2024-public/tree/main/web/simple_calculator/dist)

## Solution (Unfinished)

It seems like the intended solution is to exploit the use of
<code>eval()</code> in the PHP script (see Attachments) in order to do some remote code execution. However, there is a regex
check for alphabetic characters and quotes before <code>eval()</code> is called. I'm not sure how to
execute any meaningful command with these constraints.

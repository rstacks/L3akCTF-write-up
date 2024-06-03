# Hidden

## Description

We all start with baby steps.

## Attachments

[hidden](https://github.com/L3AK-TEAM/L3akCTF-2024-public/blob/main/rev/hidden/dist/hidden)

## Solution

We are provided a binary called "hidden." I uploaded this executable to the Decompiler Explorer at
[dogbolt.org](https://dogbolt.org/). This provides us with several C programs that were constructed from the binary. I
examined the [C code provided by Ghidra](https://github.com/rstacks/L3akCTF2024-writeup/blob/master/REV/Hidden/decompiled_binary.txt) and noted the function <code>FUN_001013e5()</code>, which appeared to be
the <code>main()</code> function, as it seemed to have a mechanism for evaluting input (it would use <code>puts()</code> to 
output "Correct!" or "Wrong!"). Within this function was a call to another function called
<code>FUN_0010137d()</code>, which seemed to return the string to compare to. Examining this function revealed the
following sequence of hexadecimal numbers:

```
0x4c, 0x33, 0x41, 0x4b, 0x7b, 0x62, 0x34, 0x62, 0x79, 0x5f, 0x73, 0x54, 0x33, 0x50, 0x73, 0x7d
```

Converting these numbers to their equivalent ASCII characters revealed the flag.

## Flag

L3AK{b4by_sT3Ps}

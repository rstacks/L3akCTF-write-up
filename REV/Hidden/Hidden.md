We are provided a binary called "hidden." I uploaded this executable to the Decompiler Explorer at
dogbolt.org. This provides us with several C programs that were constructed from the binary. I
examined the C code provided by Ghidra and noted the function FUN_001013e5(), which appeared to be
the main() function, as it seemed to have a mechanism for evaluting input (it would use puts() to 
output "Correct!" or "Wrong!"). Within this function was a call to another function called
FUN_0010137d(), which seemed to return the string to compare to. Examining this function revealed the
following sequence of hexadecimal numbers: 0x4c,0x33,0x41,0x4b,0x7b,0x62,0x34,0x62,0x79,0x5f,0x73,
0x54,0x33,0x50,0x73,0x7d. Converting these numbers to their equivalent characters on the ASCII table
revealed the flag.

flag: L3AK{b4by_sT3Ps}

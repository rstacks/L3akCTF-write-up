Never figured this out. It seems like the intended solution is to exploit the use of
eval() in the PHP script in order to do some remote code execution. However, there is a regex
check for alphabetic characters and quotes before eval() is called. I'm not sure how to
execute any meaningful command with these constraints.

# Really Simple Algorithm

## Description

Like I said, it's really simple!

[Build](https://github.com/L3AK-TEAM/L3akCTF-2024-public/tree/main/crypto/Really-Simple-Algorithm/build)

## Attachments

[server.py](https://github.com/L3AK-TEAM/L3akCTF-2024-public/blob/main/crypto/Really-Simple-Algorithm/dist/server.py)

## Solution (Unfinished)

I can tell that there is an RSA encryption happening here, but
I'm not sure how to successfully decrypt the flag with the information given. My thought was
that I need to somehow find the prime factors _p_ and _q_ of _n_ (which is provided), but _n_ is too large
for this be done without the help of an algorithm. You can see my attempt to find the prime factors
[here](https://github.com/rstacks/L3akCTF2024-writeup/blob/master/CRYPTO/ReallySimpleAlgorithm/rsa.py).

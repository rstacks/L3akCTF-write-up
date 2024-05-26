# Really Simple Algorithm

## Description

Like I said, it's really simple!

<code>nc 193.148.168.30 5668</code> 

## Attachments

[server.py](https://ctf.l3ak.team/files/36245c79edc3c493e2640638ae7cb70e/server.py?token=eyJ1c2VyX2lkIjoxNDQsInRlYW1faWQiOjYxLCJmaWxlX2lkIjozNH0.ZlOQHQ.ez5OI-Bzx6tMUX_ksOKcg23Nq7g)

## Solution (Unfinished)

I can tell that there is an RSA encryption happening here, but
I'm not sure how to successfully decrypt the flag with the information given. My thought was
that I need to somehow find the prime factors _p_ and _q_ of _n_ (which is provided), but _n_ is too large
for this be done without the help of an algorithm. You can see my attempt to find the prime factors
[here](https://github.com/rstacks/L3akCTF2024-writeup/blob/master/CRYPTO/ReallySimpleAlgorithm/rsa.py).

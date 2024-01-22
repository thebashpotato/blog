+++
author = "Matt Williams"
title = "A Guide to Bits and Bytes"
date = "2024-01-22"
description = "My take on bit masking, bit manipulation, and boolean algegra (WIP)"
tags = [
    "Bits",
]
categories = [
    "Low level programming",
]
series = [""]
aliases = []
+++

## Preface

> Welcome to the world of bitwise operations, where we don't just count sheep to fall asleep – we shift them left and right!
> If you've ever wondered what your computer is up to while you're swiping left or right on your favorite app, you're about to dive into the nitty-gritty of it.
> Bitwise operations are like the secret handshakes of the digital world; they're how computers whisper sweet nothings to each other in the language of 0s and 1s.
> So, buckle up and put on your thinking cap – or should I say, your 'bit'-ing cap? – as we embark on a journey through the land of ANDs, ORs, NOTs, and XORs.
> Who said bits and bytes couldn't be fun?

### Bits and Bytes and Words Oh My

> At the heart of every computer lies a maze of transistors, akin to tiny switches that govern the flow of electricity.
> These transistors operate on a simple principle: they're either in an 'on' state or an 'off' state, echoing the binary language of ones and zeros.
> This binary foundation underpins all computing operations, starting at the most fundamental level with bits.


| **Bits**&nbsp;&nbsp;&nbsp;     | **2^n**&nbsp;&nbsp;&nbsp;  | **Max Value (2^n - 1)**&nbsp;&nbsp;&nbsp; |
| ---------- | --------- | ----------------- | ---------- |
|  1  |  2     | 1 |
|  2  |  4     | 3 |
|  3  |  8     | 7 |
|  4  |  16    | 15 |
|  5  |  32    | 31 |
|  6  |  64    | 63 |
|  7  |  128   | 127 |
|  8  |  256   | 255 |
|  9  |  512   | 511 |
|  10 |  1024  | 1023 |
|  11 |  2048  | 2047 |
|  12 |  4096  | 4095 |
|  13 |  8192  | 8191 |
|  14 |  16384 | 16383 |
|  15 |  32768 | 32767 |
|  16 |  65536 | 65535 |


# LINE DemoS Bot - CHRLINE API

![logo](/examples/assets/logo.png)

## What's up
Since `CHRLINE` has been archived, I will update it in my own name as `CHRLINE-Patch`

#### What is my original intention?
CHRLINE is supposed to be a library for **debugging**
But as time went by, many users began to ask questions about risk control and API service restrictions, which means it could be used for any business activity.
**Finally**, I decided not to update CHRLINE after 2023/09/19
And archived the library on 11/20 of the same year

#### So why?
This is not `CHRLINE`, this is `CHRLINE-Patch`
So I think I'll keep updating it :)

---
>What is CHRLINE?\
>It is LINE Chrome API, just for debug

>If you can help update this project, \
Welcome join our [Discord](https://discord.gg/vQrMbjA)

## About Project
This project is for debug only, because it does not use thrift

So I don't recommend you to use this to run the bot, even if it has many functions

## What can it do?
If you have a certain degree of understanding of Line thrift, then you must have heard of **TMoreCompact** \
But for most people, it is difficult to decompile TMoreCompact, even if it has lower confusion in some version \
But if you can use this project to understand the differences in LINE thrift

## TMoreCompactProtocol
We added the simple function of TMoreCompact for the [first time on 26 May](https://github.com/DeachSword/CHRLINE/commit/3192377714730ddf83208836661182d641d21cb0) \
And added TMoreCompact to [the development version at Jul 8](https://github.com/DeachSword/CHRLINE/commit/d7d8430e74417a06c9ad159a5675b7787ec75c54) \
It's based on the thrift of the LINE Android version \
Its purpose is to effectively compress mid (32 bytes) to 16 bytes



####  Example


####  Requirement
- Python 3.6
    - pycrypto
    - pycryptodome
    - xxhash
    - httpx[http2]
    - gevent

## Thanks 
`This project got their help directly/indirectly, thank them deeply`
 * [fadhiilrachman](https://github.com/fadhiilrachman)
 * [ii64](https://github.com/ii64)
 * [ドマオー](https://github.com/Dosugamea)
 * [Zero Cool](https://github.com/crash-override404)
 * [sakura](https://github.com/sakura-rip)
 * [ぐるぐる](https://github.com/f0reachARR)
 * LINE _GUILTY CROWN LOST XMAS_ & _Hey LINE!_ 's group members
 * Discord _DemoS_'s group members

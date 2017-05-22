# README.md: Obfuscated Forth Compiler Project

Implementation status: TBD

The [FORTH](https://en.wikipedia.org/wiki/Forth_(programming_language)) programming language produces very dense and very
efficient interpreted code. In order to accomplish these feats, it uses RPN (reverse Polish notation) syntax which greatly 
simplifies the interpreter. The first version of FORTH was developed in 1968 by Chuck Moore. 
It becames standardized with FORTH83 and FORTH94.

FORTH is an extremely efficient way to download dynamic scripts into an application that already has a built-in FORTH 
interpreter - similar to Lua. If we are willing to disallow dynamic editing of FORTH scripts then we can produce an extremely
compact FORTH interpreter with a size of only a few K bytes.

MP4 which is a commonly used format in the video industry. Recently MP4 allows non-video user specified payloads to be 
included in the MP4 stream. Therefore we could dynamically push FORTH scripts into the video player application which could 
be used for security purposes. We require that these scripts be obfuscated.

My proposed solution not only obfuscates the script, but obfuscates the FORTH interpreter. 
In theory we would like to see that every player app has its own version of the interpreter,
say based upon the low 4 or 8 bits of its MAC address or subscriber UUID.

There are other projects that could benefit from obfuscated Forth.

Most assembly code reverse engineering hackers dislike having to deal with VMs (i.e. virtual machines) because they don't
have the tools to automatically deal with them.

Besides implementing obfuscated FORTH in C,
today it may be worthwhile to implement it also using [Web Assembler (WASM)](http://webassembly.org/).

## --
<address>
<br>AUTHOR: Avraham DOT Bernstein AT gmail
<br>DATE: 2017-05-22T20:29:00Z
<br>Copyright (c) Avraham Bernstein, Jerusalem ISRAEL. All rights reserved.
<br>LICENSE: Apache License, Version 2.0: https://opensource.org/licenses/Apache-2.0
</address>









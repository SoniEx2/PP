# PP
Pretty Parser / Parser Processor. A C program that lets you parse while you parse.

The basic idea is that you can write macros just like a macro preprocessor, but you can also write parsers, that is, you can modify the syntax rules while you macro. This means you can write an x86 compiler with it, but not just that, you can also write a Forth compiler using the x86 compiler, or a C89 compiler with the Forth compiler with the x86 compiler!

Obviously it isn't able to do _everything_, and many times it'll probably get stuck in an infinite loop, but that can happen with normal parsers too so nothing wrong there. :P

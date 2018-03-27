# strnstr()

I kept finding perfectly good C code that wouldn't compile on the Raspberry Pi because strnstr() isn't a native Linux call. Plug this in with a simple #include "strnstr.c" and you're off to the races.

This should work for all flavours of Linux, but I have only tested it on Raspberry Pi. Please read the license for info if you find bugs or whatever. I can't provide support, but you prolly won't need it anyway.

# Lua 5.4.4 for Ultra Engine

You can use this version of Lua for building modules for use with Ultra Engine.

The only change is in luaconf.h:
```c
#define LUA_IDSIZE	4096
```
Visual Studio project and precompiled binary are provided.

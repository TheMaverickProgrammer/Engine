# boldtemple Game Engine
`version 0.2` (unstable pre-alpha) /
[Main Web](http://gaming.boldtemple.net/engine/bge/ "boldtemple Game Engine Main web") / 
[Documentation](http://boldtemplegaming.github.io/Engine/ "boldtemple Game Engine Documentation") /
[TODO](https://github.com/boldtempleGaming/Engine/wiki/TODO "TODO")

boldtemple Game Engine, build using C++11 and SDL2.
<br/>Cross Platform: `Windows`, `Linux`, `OS X`.

<br/>
___
<br/>


## Instructions
### - Build

<!--
> **Cross platform steps**
Soon..

| bgengine |
| :---- |
|`11111111111111111111111111111`|
--------------------
|  |  |
| ---- | ---- |
| a | b |
-->


<br/>**Windows**<br/>
Setup dependencies:

1. In engine root project, make new folder name it **`deps`**.
2. Inside ***`deps`*** download and extract: **[`SDL2`](https://www.libsdl.org/release/SDL2-devel-2.0.3-mingw.tar.gz")** + **[`SDL2 ttf`](https://www.libsdl.org/projects/SDL_ttf/release/SDL2_ttf-devel-2.0.12-mingw.tar.gz "SDL2_ttf-devel-2.0.12-mingw.tar.gz")** +
**[`SDL2 image`](https://www.libsdl.org/projects/SDL_image/release/SDL2_image-devel-2.0.0-mingw.tar.gz "SDL2_image-devel-2.0.0-mingw.tar.gz")**.
3. Download [MinGW](http://sourceforge.net/projects/mingw/files/latest/download?source=files) and Install it using our guide, checking what to select from [*here*](http://gaming.boldtemple.net/engine/bge/files/media/mingw_ticks.png).
4. Download [CMake](www.cmake.org/download/) tool which uses **`CMakeLists.txt`** to generate project files/makefile.
5. Generate MinGW makefile and type to console:
```
mingw32-make -j4
```
Build source:
+ Link deps with in project, generate makefile then build.

<br/>**Linux**<br/>
Install dependencies:
```
$ sudo apt-get install g++ make cmake libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev 
```
Build source:
```
$ cd /path/to/build/
$ cmake /path/to/folder/with/cmakelists
$ make -j4
```
*Where `-j4` is 4 parallel make jobs, it depends on your count of CPU cores.*


<br/>**OS X**<br/>
Soon..


<!-- **boldtemple Game Engine** -->

# CS2-External-Usermode
pretty solid features - external cs2


This is basic C++, you need to set libs and include linkers:

1)extract fhook/thirdparty/freetype/include&lib.zip in the same folder
2) go to project-> properties
3) c/c++ --> General and add Include file which was in include&lib/freetype/include(add this path in Additional Include Directories)
4) Now go to linker (below C/C++)-> general
5) add objs(include&lib/freetype/objs) in to Additional Library Directories

Port ImageMagick++ to Android

This is ported on Mac OSX with Android Studio and NDK installed. Use configure to generate Makefile and then modify Makefile to point to Android NDK folders, cc, cxx, c++, ld, ar, cflags, ldflags and remove unsupported features in the configuration header file. So, re-configure will remove all porting efforts, hence disabled commands "rm -f Makefile".

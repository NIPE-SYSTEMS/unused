# unused

This header file defines a simple macro to remove *unused parameter*-compiler-warnings. Use this macro with care: only disable compiler warnings if really needed.

## How to use

Simply include the `unused.h` into your project:

    #include "unused.h"

From now the macro function `UNUSED()` is available to remove compiler warnings:

    void multiply(int a, int b, int c)
    {
        UNUSED(c);
        
        return a * b;
    }

## License

lastest GPL-license (see LICENSE-file)

Copyright (C) 2015 NIPE-SYSTEMS, [http://www.nipe-systems.de](http://www.nipe-systems.de)

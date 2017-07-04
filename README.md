# prepro

small, lua-based preprocessor, found at http://lua-users.org/wiki/SimpleLuaPreprocessor, changed for lua 5.3

just try the examples:

    ./prepro example1

    ./prepro example2

    ./prepro example3

    ./prepro example4

    ./prepro -l \~ example5

just to show the power of lua, example 3 combines the preprocessor with the data description example from pil, found here: https://www.lua.org/pil/10.1.html
example 4 shows how to include files or call the preprocessor from inside a file.
example 5 shows how to change the symbol introducing a line of code from the default "#" to "~", in order to preprocess markdown which uses "#" a lot.

## License

found in the public domain and believed to be in it.
original author not known, maybe Rici Lake?


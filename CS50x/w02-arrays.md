<h1>Arrays | Week 2</h1> 
<h3>26/09/2022</h3>

- preprocessing
  - finds prototypes and from headers
  - or loads dependencies
- compiling
  - takes source code and turns into
  - clang is a compiler
- assembling
  - each CPU has own instruction set
  - compiles assembly to machine code
- linking
  - links dependencies and combines source code and dependencies into one

"Compiling" a general term that describes the 4 steps above.

- debugging

  - diagnose problem more practively
  - print functions useful to seeing what's going on
  - breakpoint = pause execution here
  - rubber duck = talk through the logic

- Data types - space in memory (bytes)
  - bool = 1
  - char = 1
  - double = 8
  - float = 4
  - int = 4
  - long = 8
  - dictionary = ?
  - array = stores data contiguously
    - e.g. int abc[3] = [ a, b, c]
    - not to eliminate saveing space, but prevents naming multiple variables
  - string = arrays of chars
  - nul = 1 (00000000 | \0)
    - separates one string from another
    - [h,i, ,N,i,c, /0]

- code smell = something smells off! Code can be improved.

```

// header
int string_length(string str);

// functionf
string_length(string str)
{
    int i = 0;
    while (str[i] != '\0')
    {
        i++
    }
    return i;
}

```
- void = function doesn't take CLI arguements
```
#include <stdio.h>

int main(int argc, string argv[])
{

}

```
- argc = arguement count (stores how many words CLI typed)
- argv[] = arguement vector
    - array of words that human typed at the prompt
- exit status
    - return non zero value from main()
      - this allows for multiple error codes (int has 4 bytes)
      - returning 0 assumes programme is working correctly

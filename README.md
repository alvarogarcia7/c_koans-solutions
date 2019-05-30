# c_koans

## Running the koans

```bash
docker run -v $(pwd):/app -it conanio/clang7 /bin/bash

## inside docker
export LD_LIBRARY_PATH=/usr/local/lib:/app/criterion/lib/
make clean all
./bin/c_koans
```


## Sections

Inside `src/` you will find a file for each of the following topics in C:

- Basics
- Pointers
- Functions
- Arrays
- Strings
- The Preprocessor
- Control Statements
- Structs
- Dataclasses
- I/O
- Malloc
- Linked List Project

The recommended order for fixing the tests is:
- about_basics.c
- about_control_statements.c
- about_functions.c
- about_pointers.c
- about_malloc.c
- about_arrays.c
- about_strings.c
- about_structs.c
- about_dataclasses.c
- about_printing.c
- about_io.c
- about_linked_lists.c
- about_preprocessor.c

# R24-Test-Hex-Editor
This repo contains source files for hex editor.
This generates hexdump and edited hexdump to binary file.
The `tests` folder contains units tests

## Instructions
1. Fork this repo
2. Select an ISSUE to work on from the ISSUES section
4. Commit and push your changes to the fork
5. When told, make a PULL REQUEST describing the changes and include the details.

# Building
The unit tests can built and run as follows:
```
$ cd tests
$ gcc *.c ../utils.c -I .. -o test_hx.out
```
Above example builds the `test_hx` unit test. It tests both the functionalities. It can be run as follows:
```
$ ./test_hx.out
test_hx.c:59:test_hx:PASS

-----------------------
1 Tests 0 Failures 0 Ignored
OK
```
All test cases pass, in this case.
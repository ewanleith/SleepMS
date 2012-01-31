# Sleep MS

Simple Linux program to sleep for a number of milliseconds, instead of seconds

## Installation

Either download the executable and copy somewhere locally, or download the C source code and compile it using

gcc -o sleepms sleepms.c

## Usage

Simply run the command with 1 parameter, the number of milliseconds to sleep

./sleepms 1500

Will sleep for 1500 milliseconds (1.5 seconds).

If you pass multiple parameters, or a non-integer value, the command will return immediately.

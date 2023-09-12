I made a racing game in C++. Explanation: The cursor is placed at the specified
location on the screen using the gotoxy() function. This indicates that the gotoxy()
method can be used to move the cursor on the screen. Its main purpose is to print
text wherever the pointer is placed. COORD: is a frame for holding screens. X and
Y are COORDINATE. A handle to a standard device is returned by the
GetStdHandle (input, output or error) function. A handle is an access point to a
Windows kernel object provided by an index in the system table. I believe Std
Output Handle() returns the value STD OUTPUT HANDLE to identify the active
console buffer for standard output. The cursor location is set using
SetControlCursorPosition. The standard input (STDIN), standard output (STDOUT)
and standard error handles (STDERR) can be retrieved using the GetStdHandle()
method. Only one argument, STD_INPUT_HANDLE, STD_OUTPUT_HANDLE or
STD_ERROR_HANDLE, is required for the GetStdHandle() function. The built-in
srand() function is part of the C++ STL, which is a header file specified in cstdlib.
Random number generators are initialized using the srand() function. The srand()
function sets the initial value for a pseudorandom number stream. The rand()
functions are set as if srand(1) were called at program startup if srand() is not
invoked. The generator starts from a different starting point if the function is set
to any other value.

### C++ Review

##### ```int main(int argc, char * argv[], char * envp[])```

```int argc``` counts the number of command line arguments that ```argv[]``` holds for this current program execution, includes the object program itself, hence must be >= 1, is ```main()```’s first formal parameter.

```char * argv[]``` is a pointer to the list of actual const string arguments.2nd formal parameter of ```main()```; optional; if specified, the first parameter ```argc``` must already be specified.

```char * envp[]``` holds environment variables as string constants, plus the header: ```PATH=```. 3rd formal and optional parameter of ```main()```.

#### Pointers

```&``` is the address-of operator, and can be read simply as "the address of".

```*``` is the dereference operator, and can be read as "value pointed to by".

[Tutorials from cplusplus.com](http://www.cplusplus.com/doc/tutorial/pointers/) about pointers.


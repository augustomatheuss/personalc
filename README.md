# personalc
My personal reference to C programming  


## Usage examples in file examples.c  
* Compile - Command Line 
```
gcc -lm examples.c personal.c -o examples
```  
* Compile - Makefile
```
make && make clean
```
* Run
```
./examples
```

## Check memory leaks in your program  
```
valgrind --leak-check=full --track-origins=yes name-of-your-program
```

## References:  
* http://www.cplusplus.com/reference/clibrary/  

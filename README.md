# watchc
Checks once a second if source file changees then compiles and runs the program

## Use
In the root folder with your C program run

``` $ watchc source.c compiled ```

Modify script as needed. It runs ``` $ gcc -o compiled source.c ``` when file change detected. then auto starts compiled executable. All paths are relative.
script will create .watchlog file

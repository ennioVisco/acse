#ACSE COMPILER

## DEPENDENCIES

Before installing the compiler, you should install **make/cmake**, **flex** and  **bison**. To do so in Ubuntu you can simply type in the console:

```
apt-get install make
apt-get install cmake
apt-get install flex
apt-get install bison

```

## INSTALLATION

To install the ACSE compiler type in the console:

```
 make

```

## COMPILATION
To compile some examples (located in the directory **./tests**) type:

```
 make tests

 ```

In order to use the compiler/assembler/executor at first you have
to export the directory ./bin in your current PATH as follows:


```
export PATH=`pwd`/bin:$PATH
```

You can compile and run new Lance programs in this way (suppose you
have saved a Lance program in 'myprog.src'):

```
 acse myprog.src myprog.asm
 asm myprog.asm myprog.o
 mace myprog.o
```

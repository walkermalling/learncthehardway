
## Use `make`

`make <filename>` looks for filename.c and compiles it to filename

`-Wall` flag sets reporting to verbose

## Make a file with a `Makefile`

```
CFLAGS=-Wall -g

clean:
   rm -f <filename>
```

then,

```
$ make clean
$ make <filename>```
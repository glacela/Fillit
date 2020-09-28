### Hive Helsinki
# Fillit
Group project for Hive Helsinki called Fillit. In this project you are asked to create a program that can validate and sort given tetrominos in the smalles possible square without turning them reading the shapes from a file.
* [Subject](https://cdn.intra.42.fr/pdf/pdf/6621/fillit.en.pdf)

### Compiling & Use

Run `make` and an executable called fillit should compile in the current location.

Run `./fillit [file]` for the program itself.

Example:

```
$> cat -e example
....$
..##$
..##$
....$
$
.##.$
.#..$
.#..$
....$
$>
$> ./fillit example
BB.
BAA
BAA
$>
```

### Authors
This was a group project done by me and [jmerilai](https://github.com/merkkari)

# set-fns


Simple CLI for basic set operations over single column files.

## Installation

```sh
$ pip install set-fns
```

## Usage

```sh
$ set-fns intersection a.txt b.txt c.txt
```

## Examples

```sh
$ cat a.txt     $ cat b.txt
1               1
2               3
3               5
4               6
5

$ set-fns intersection a.txt b.txt
1
3
5
final set cardinality: 3

$ set-fns union a.txt b.txt
1
3
2
5
4
6
final set cardinality: 6

$ set-fns difference a.txt b.txt
2
4
final set cardinality: 2
```

## License
MIT

Enjoy :)

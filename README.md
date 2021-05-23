# cli0
_(cleo)_ cli zero —a simple shell script skeleton with no dependencies

Good for whipping up a quick command line tool with some familiar comforts:
- argument parsing
- usage info
- colored output (when appropriate) that goes to [the right place](https://man7.org/linux/man-pages/man3/stdout.3.html)

cli0 doesn't really do anything out of the box; it provides a template to be modified for your own purposes:

```console
$ ./cli0
provides the skeleton of a simple cli

usage:
  cli0 [<service> | --<option>]

options:
  -h --help   show this usage info
  <service>   foo, bar, baz
```

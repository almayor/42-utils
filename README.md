## 42-utils

A collection of useful scripts for working on projects @ [School 42](https://en.wikipedia.org/wiki/42_(school)).

### Overview

1. `proto-list`
	* A python script that extracts and prints a sorted list of all non-static function prototypes (including cases where prototypes span multiple lines). Source files are searched recursively, starting from a given directory. Useful for creating / updating headers.
	* `Usage: proto-list <directory>`

2. `src-list`
	* A shell script, recursively searching and printing a sorted list of `.c` files in a directory. Useful for pasting into Makefiles, since the [Norme](https://github.com/almayor/libft/blob/master/docs/subjects/norme.en.pdf) doesn't allow wildcards.
	* `Usage: proto-list <directory>`

---
If you have any questions, please contact me on Github.

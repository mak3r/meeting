# Bash functions to quickly take notes

```
Usage: 	meeting [-tyldhrs] [filename]
	Basic usage 'meeting <filename>'
	Create a file specified by <filename> in the path indicated by date.
	Assume todays date unless one of t, y or d are specified
	  t - use tomorrow's date
	  y - use yesterday's date
	  d - use date specified by date format. Specify 9 days ago for example 'meeting -d "-v -9d +%Y/%m/%d"'
	  D - use todays date as the basis for adding or subtracting days. Use with -l for example 'meeting -l -D "-2"'
		 Be sure to quote the argument to -D otherwise the '+' or '-' will be interpreted by the shell.
	  f - find file entries with name
	  l - list files on date. If <filename> is specified, it is ignored.
	  r - specify the root directory to use
	  s - show the root directory being used
```

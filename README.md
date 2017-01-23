# Pensieve
This is a diary script.

You can add or read a diary, or you can view it's stats.

Oh, and it's prodected with a symetric encryption from GPG (should be AES-128 or something similar string).

## Usage

```
./pensieve [OPTIONS] MODE [FILE]

OPTIONS:
	-p	use pager (only in read-mode)
	-q	quiet (no output except the content)
	-j DATE	jump to DATE (implies -p)
		DATE	YYYY.MM.DD

MODE: {test|stat|read|add}
	test	check password
	stat	print size, number of entries, ...
	read	read diary
	add	add entry

FILE: the diary file
```

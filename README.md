ClassCalendar
=============

This is a simple python script to create an HTML calendar. The script is
compatible with both python 2.7 and python 3. It uses only the python standard
library, no external libraries are needed. The best means to understand what
goes into a specification file is to read the example in the repository.

To be clear, you only need the gencal script. The other files are there as
example input and example style sheets.

Usage
-----

The script takes an INI specification file and draws an HTML file into the
second filepath.

```bash
$ gencal ini-spec-file output.html
```


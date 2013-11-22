Class Calendar
=============

This is a simple python script to create an HTML calendar containing the topics
that will be discussed on any given class day. The generator allows the user to
create a calendar rather simply. All that is needed is the class start and end
dates, the pattern of the days (e.g. MWF or TR), and a series of topics that
will be discussed on any given class day. The generator also accepts some
optional content, holidays for example.

The user tells the script about the class using a specification file. The
specification file is a plain INI file. The best means to understand what goes
into a specification file is to read the example in the repository.


Requirements
------------

The script is compatible with both python 2.7 and python 3. It uses only the
python standard library, no external libraries are needed.


Usage
-----

The script takes an INI specification file and draws an HTML file into the
second filepath.

```bash
$ gencal ini-spec-file output.html
```

To be clear, you only need from this repository is the gencal script. The
other files are there as example input and example style sheets.


Tasks
===
Answer the following questions, using the suitable markdown syntax, e.g., add headings, subheadings, numbered lists, HTML-link and code blocks.

(i) Give a URL where the module datetime in the Python Standard Library is documented.

(ii) What does 'Explicit Type Conversion' mean?

(iii) What date and time will it be in ten days, according to the output of your modified program.


Answers
---

(i) The datetime module documentation can be found at [https://docs.python.org/3/library/datetime.html]

(ii) _Explicit Type Conversion_ is used when Python can not deduce the type automatically, e.g. if you want to get the integer value out of a string, ``int('12345')``

(iii) The following output is produced:
```
    Current date and time: 2024-09-10 22:50:48.701758
    In ten days it will be the date and time: 2024-09-20 22:50:48.701758
```
Thus, in ten days the date/time will be 2024-09-20 at 22:50

More tasks
===
Augment the text to also include the following: (i) Describe some functionality in the datetime module that you find useful. (ii) Add a practical example of how explicit type conversion is used in Python (for instance copy-paste from the code above) (iii) For the libraries you listed in Task g, indicate which belong to the Standard Python Library and which are external libraries.

Answers
---
(i) Some useful functionality in the datetime library is:
- The ability to get the current system time (using the ``datetime.now()`` function)
- Manipulating datetime objects with flexible delta operations
- Parsing arbitrary date/time strings with ``datetime.strptime()``
- Customize output format with ``datetime.strftime()``

(ii) A practical example of explicit type conversion is:
``str(datetime.now()`` where a datetime object is converted into its' default string representation

(iii) __Standard python libraries__: _os, glob, unicodedata, math, string, hashlib, json, typing, types, struct, io, collections, re, itertools, time, sys_. __External libraries__: _sklearn, gensim, numpy, matplotlib, mpl_toolkits, scipy, bidi.algorithm_

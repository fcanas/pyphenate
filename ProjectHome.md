pyphenate is a text hyphenation program for the web. HTML processed with pyphenate will automatically break across lines to produce better looking text than is currently typically seen across the web.

W3C specifies that a "soft hyphen" is a character denoting where a word can be broken across a line break. When a word is broken there, a hyphen is shown. The soft hyphen is not shown, and ignored at all other times.

pyphenate processes HTML and inserts soft hyphens in appropriate places in words inside p blocks. It leaves all other markup and content untouched.

See an example of a page that has been processed with pyphenate [here](http://www.fabiancanas.com/stylesheets/pyphenateExample.html).
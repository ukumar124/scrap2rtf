2014-03-10  Andrey "Ivnish" Ivnitsky <ivnitsky.a@gmail.com>

> version 0.5
  * New command line option (-s --same-directory), convert files in a same directory where is a scrap
  * Support MSO 2010 scraps

2012-10-28  Andrey "Ivnish" Ivnitsky <ivnitsky.a@gmail.com>

> version 0.4
  * Fix a bug, when convert to RTF
  * Code comments translate to English (Sorry for my English)
  * Fix read from stdin (now can use: cat scrap.shs | scrap2rtf, find . -name '.shs' | xargs -d '\n' scrap2rtf)

2012-10-07  Andrey "Ivnish" Ivnitsky <ivnitsky.a@gmail.com>

> version 0.3
  * New parameter, -o/--output, to use the custom directory for converted scraps
  * Fix a bug where the scraps were in the current directory
  * More UNIX-way, now program process any count files (as cat and another utilites)
  * With no FILE, or when FILE is -, read standard input (as cat and another utilites)

2012-09-30  Andrey "Ivnish" Ivnitsky <ivnitsky.a@gmail.com>

> version 0.2
  * More UNIX-way. Now the program processes only one file for time.
  * Added analysis of type of a scrap (doc/docx, xls/xlsx) and use of corresponding algorithm of unpacking is. (Depends: p7zip-full)
  * Rewrite source code from C language to C++

2010-05-16  Andrey "Ivnish" Ivnitsky <ivnitsky.a@gmail.com>

> version 0.1
  * Initial release.

ChangeLog ends here

A cheatsheet for diagnostic and troubleshooting commands that I made for my
developer colleagues at Songkick.

We use Ubuntu, so it's mostly focussed on that.

To generate a printable page I do this:

    pandoc -f markdown -o cheatsheet.html cheatsheet.md     # any markdown processor should work
    xdg-open cheatsheet.html || open cheatsheet.html        # should work on ubuntu & Mac OS X

I then print it out at two pages per side, which is currently a single side of A4 paper.

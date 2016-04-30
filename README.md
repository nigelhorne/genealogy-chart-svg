This fork from davorg/genealogy-chart-svg adds the 'generate' program
which takes a Gedcom and generates an input file to the chart program.

For example:
    ./generate -m 5 -h 'Nigel Horne' gedcom.ged | sort -n | ./chart > horne.svg
    gimp horne.svn (or use open horne.svg on MacOS/X)

On MacOS/X, translate to a PNG using:
    qlmanage -t -s 5000 -o . horne.svg

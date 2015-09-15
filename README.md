This fork from davorg/genealogy-chart-svg adds the 'generate' program
which takes a Gedcom and generates an input file to the chart program.

For example:
	./generate -m 5 -h 'Nigel Horne' gedcom.ged > horne.dat
	./chart horne.dat > horne.svn
	gimp horne.svn (or use open horne.svg on MacOS/X)

TODO:  Modify chart to read STDIN so that a pipeline can be created.

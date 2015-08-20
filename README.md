# SimpleTable
A Python module for simple table building, manipulation, and output in various formats.
This module is intended to work with Python 2.7+ (including Python 3 versions).

Basic use:

           mydata = [[11,12],[21,22]]  # data MUST be 2-dimensional
           myheaders = [ "Column 1", "Column 2" ]
           mystubs = [ "Row 1", "Row 2" ]
           tbl = SimpleTable(mydata, myheaders, mystubs, title="Title")
           print( tbl )
           print( tbl.as_csv() )


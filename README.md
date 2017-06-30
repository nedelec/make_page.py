# make_page.py
Create HTML master page with links to images and movies

Synopsis:

    `make_page' generates an HTML page linking images & movies found in sub-directories

Usage:
    
    make_page.py [recursive=1] [tile=INT] [width=INT] [height=INT] [OUTPUT] DIRECTORIES

Info:
    
    If `tile` is set, a HTML table will be generated, and the value specified will be the
    number of entries in each line. The name of the ouput file ('page.html' by default), 
    can be specified on the command line (extension should be .html).
    `width` or `height` specify the size in pixels at which images will appear on the HTML.


Copyright F. Nedelec, EMBL
Created  14.12.2007
Modified 3.2010, 5.2012, 11.2012, 7.2013, 11.2013, 4.2015

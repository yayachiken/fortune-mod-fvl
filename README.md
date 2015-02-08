Building & Installing
---------------------

strfile(1) is part of the fortune package.

To build the fortune database, run

    strfile fvl
    
or

    strfile fvl-vendor
    
respectively.

The fortunes can then be installed (assuming your fortune directory is
/usr/share/fortune) with:

    cp fvl* /usr/share/fortune

For instructions on how to scrape the posts from Usenet or how to
convert them to HTML, please visit [the original project page at 
SourceForge][1].



Acknowledgments
------------------

This collection is just a UTF-8 conversion from the fortune-mod-fvl
package [originally hosted on Souceforge][1].

To copy the original acknowledgement:

The fortunes were extracted from archived Usenet postings at
www.google.com. Many thanks to their authors, especially
Felix von Leitner (http://www.fefe.de).

[1]: http://sourceforge.net/projects/fortune-mod-fvl

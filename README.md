extract_ev_data
===============
Pure Python program used to extract EV data from Mozilla CA roots. Used to generate EV validation data in sslyze.


Description
-----------
Simple Python test program that extracts EV data from
the Mozilla CA root source code. The program is a replacement for
the
[extract_mozilla_ev_oids.py](https://github.com/nabla-c0d3/extract_mozilla_ev_oids)
extract program that requires Windows CPP or other C compiler.

The extractor part of the code is fairly generic and should be
able to parse similar structs. The output generator is
fully source agnostic.


Notes
-----
This code assumes Python 2.6.x.

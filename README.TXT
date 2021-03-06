#	$Id: README.TXT 604 2017-04-01 06:35:09Z pwessel $
#
#	Authors: Paul Wessel and Joaquim Luis
#	Updated: Feb 23, 2017

The Matlab/Octave API is built on top of the GMT C/C++ API
and is therefore decoupled from the GMT5 distribution.  We
anticipate this is how other APIs (Python, Julia) will be
done as well.  To build gmtmex you first must install
GMT >=5.3.2 from subversion or via an official release.

The single gmtmex.c program is linked with gmtmex_parser.c and
the GMT5 API library into a mex executable. A configure option
selects between Matlab versus Octave builds.  The script
gmt.m is responsible for calling the gmtmex executable.


To install, build, or debug the mex please see the wiki for gmt-mex at
http://gmt.soest.hawaii.edu/projects/gmt-MATLAB-octave-api/wiki

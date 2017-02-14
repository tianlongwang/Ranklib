This Lemur project release is for Indri 5.11, Galago 3.11, RankLib-2.8 and Sifaka-1.0.

Applications compiled with the Indri API require the following libraries:
   z, iberty, pthread, and m on linux. 

Applications built in Visual Studio require the additional library wsock32.lib.

The java jar files were built with Java 8 (jdk 1.8.0). The java UIs require Java 8.
We have tested using GCC 4.4.7 (CentOS 6.7 linux), 4.8.4 (Ubuntu 14.04 and 16.04
linux), 4.2.1 (OS/X 10.11.3), and Visual Studio 2012 (Windows 7, WIN32 and x86_64).

Note that OS/X Yosemite (10.10) is not supported at this time.
Note also that  Windows 10 is not yet supported.  Indri built with Visual Studio 
beyond version 2012 has not been tested.

No further development is being done with Indri.  Future releases beyond version
5.11 will be for bug fixes only.


Bug Fixes

  See https://sourceforge.net/p/lemur/bugs/ for the complete ticket listing.

  o BUG# 286  Galago build-special function works after clearing job directories.

  o BUG# 289  Change document ID arguments for Galago Retrieval get document methods
              from integer to long.  Updated appropriate unit tests.

  o BUG# 290  Incorrect indri version number posted in index build manifest.


Non-Ticket Feature Additions

  o Slight RankLib processing improvements by changing string comparison methods.

  o Additional unit tests in support of internal or external IDs for Galago document
    working sets.

  o Add simple name, rank score debug information in Galago SimpleEvalDoc. 

  o Removal of white space after colon in Galago simple query field searches.

  o Ignore blank strings in Galago parameter argument passing.

  o Updated Galago caching library.

  o Make Galago WordLists threadsafe.


Addition of Sifaka-1.0, a text mining application, to Lemur Project software.  See
https://www.lemurproject.org/sifaka.php for details.





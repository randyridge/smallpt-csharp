smallpt-csharp
==============

smallpt: Global Illumination in C#
(http://www.kevinbeason.com/smallpt/)

This is a port of Kevin Beason's smallpt to C#. Please visit Kevin's site for more information.

My purpose is to have a comparison point as I'm going to refactor it for my own amusement and education...  This is similar to what Ronald Chen did in Java (http://pyrolistical.github.com/smallpt/).

I used my C++ version (http://github.com/randyridge/smallpt-cplusplus) as a starting point.  I tried to keep it as close to the C++ version as I could...  There's currently some issues with the multi-threading portion (I believe some serious false sharing), I'll see if I can correct it and get it merged soon.

For handy timing use the following from PowerShell:
Measure-Command {.\smallpt.exe 5000}

Please note that running 5000 samples will take quite a long time (perhaps start with a much lower number) and I've disabled status indicators.

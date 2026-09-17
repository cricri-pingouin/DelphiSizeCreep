Over time, I have compiled one of my project [SliSame](https://github.com/cricri-pingouin/SliSame) with different versions of the Delphi IDE.

Below is a list of the built executable (SliSame.exe) and size, with no changes whatsoever to the source code.

Delphi version | Year released | Built executable size (bytes)
--- | --- 
Delphi 7 | 2002|  508,928
Delphi 2006 (Turbo Delphi) | 2005 | 508,928
Delphi 2010 | 2009 | 973,312
XE | 2010 | 982,016
XE2 | 2011 | 1,353,728
Delphi 11 | 2021 | 2,188,800
Delphi 13.1 | 2025 | 2,275,328

For some reason, Delphi 7 and Delphi 2006 (Turbo Delphi) seem to build the exact same size. I have checked the 2 files hashes and they are different, so presumably I didn't mess up and mislabel.

For fun, here is a chart:


And for more fun, with a not too shabby R^2 value of 0.9648, the data predicts the size of this executable at any year to be:

Executable size (bytes) = 

E.g. in 2040, my SliSame.exe executable size is predicted (?) to be:

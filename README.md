Over time, I have compiled one of my projects, [SliSame](https://github.com/cricri-pingouin/SliSame) (for no particular reason), with different versions of the Delphi IDE.

Below is a list of the built executable (SliSame.exe) size, with no changes whatsoever to the source code.

Delphi version | Year released | Built executable size (bytes)
--- | --- | ---
Delphi 7 | 2002 |  508,928
Delphi 2006 (Turbo Delphi) | 2005 | 508,928
Delphi 2010 | 2009 | 973,312
XE | 2010 | 982,016
XE2 | 2011 | 1,353,728
Delphi 11 | 2021 | 2,188,800
Delphi 13.1 | 2025 | 2,275,328

For some reason, Delphi 7 and Delphi 2006 (Turbo Delphi) seem to build the exact same size. I have checked the 2 executable files hashes and they are different, so presumably the matching size is purely coincidental and not the result of an error on my part.

For fun, here is a chart of the executable size evolution over time:

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/a4349a57-0c7f-4297-b74d-3a4de56df1a7" />

And for more fun, with a not too shabby R^2 value of 0.9648, the data predicts the size of my 0.49MB [SliSame.exe](https://github.com/cricri-pingouin/SliSame/releases/tag/v1.01) executable compiled with the latest IDE to be:

Size (bytes) = 86337.37 * year of Delphi IDE release - 172442581

Year | Executable size (MB)
--- | ---
2030 | 2.69
2035 | 3.10
2040 | 3.51
2045 | 3.93
2050 | 4.34

FsLab project templates
=======================

This repository hosts FsLab project templates compatible with all F# editors.
To get started, download the template as a ZIP file, extract the files and 
open it in your favorite editor. Some editors will download FsLab packages
on build, in others, you need to explicitly run [paket install](http://fsprojects.github.io/Paket/paket-install.html).
For example, when using mono on Mac, run:

    mono .paket/paket.bootstrap.exe
    mono .paket/paket.exe install

The repository currently hosts the following templates:

 * [Basic FsLab template](https://github.com/fslaborg/FsLab.Templates/archive/basic.zip) -
   references FsLab and gives you a single script file with simple demo

 * [FsLab Journal template](https://github.com/fslaborg/FsLab.Templates/archive/journal-vs.zip) (Visual Studio only) -
   in addition to the above, this lets you write literate FsLab scripts and produce HTML or LaTeX reports

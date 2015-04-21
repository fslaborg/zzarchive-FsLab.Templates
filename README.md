FsLab project templates
=======================

This repository hosts FsLab project templates compatible with many F# editors.
Using the templates, you can start with FsLab in 3 simple steps:

 1. Download a selected template
 2. Build it to download FsLab packages
 3. Open scripts  in your editor & play!

### 1. Download a template

To get started, download a branch with the template as a ZIP file and extract the files.
The repository currently hosts the following templates:

 * [Basic FsLab template](https://github.com/fslaborg/FsLab.Templates/archive/basic.zip) -
   references FsLab and gives you a single script file with simple demo
 * [FsLab Journal template](https://github.com/fslaborg/FsLab.Templates/archive/journal-vs.zip) (Visual Studio only) -
   in addition to the above, this template also lets you write literate FsLab scripts and produce HTML or LaTeX reports
 * **FsLab Journal template** (Cross-platform) - cross-platform version of the above [Work in progress!]
 
### 2. Build the template

Visual Studio and Xamarin Studio should download FsLab packages automatically on build.
If this doesn't happen (or when using other editors), you need to explicitly run
[`paket install`](http://fsprojects.github.io/Paket/paket-install.html).
For example, when using mono on Mac, run:

    mono .paket/paket.bootstrapper.exe
    mono .paket/paket.exe install

This installs the FsLab dependencies into `packages` folder and you're ready to go!

### 3. Use FsLab for fun & profit!

Once you have the template and packages, you can open the `Tutorial.fsx` file and start playing
with FsLab. For more information, see the [Getting Started](http://fslab.org/getting-started/) page on www.fslab.org.

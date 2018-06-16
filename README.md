Deep Learning Book
==================

**This is a skeleton for Deep Learning Book Chinese Version.**

## Compile the LaTeX Source Code

To compile the source code to a PDF file, please make sure you have a latest TeX
system installed. You can download and install a TeX distribution for your
platform from http://tug.org.

It's recommended to install:

- [Tex Live](http://tug.org/texlive/) 2015 or later for Linux
- [MacTex](http://tug.org/mactex/) 2015 or later for Mac OS X

### Check out source code

Use git to clone this repository and the code samples as a sub module:

```shell
$ git clone https://github.com/tigerneil/dlbook-zh-cn.git
```

### Prepare Fonts

Run the `bootstrap.sh` in the working copy to download required fonts:

``` shell
$ ./bootstrap.sh
```

This is a simple shell script to download the following free fonts into `fonts/` folder:

- [Google Noto Sans CJK SC](https://noto-website-2.storage.googleapis.com/pkgs/NotoSansCJKsc-hinted.zip)
- [Google Roboto](https://github.com/google/roboto/releases/download/v2.134/roboto-unhinted.zip)
- [Adobe Source Serif Pro](https://github.com/adobe-fonts/source-serif-pro/archive/1.017R.zip)
- [Adobe Source Code Pro](https://github.com/adobe-fonts/source-code-pro/archive/2.030R-ro/1.050R-it.zip)

You can also manually download and unarchive to `fonts/`, and make sure it contains:

```shell
fonts/
├── NotoSansCJKsc-Black.otf
├── NotoSansCJKsc-Bold.otf
├── NotoSansCJKsc-DemiLight.otf
├── NotoSansCJKsc-Light.otf
├── NotoSansCJKsc-Medium.otf
├── NotoSansCJKsc-Regular.otf
├── NotoSansCJKsc-Thin.otf
├── NotoSansMonoCJKsc-Bold.otf
├── NotoSansMonoCJKsc-Regular.otf
├── Roboto-Black.ttf
├── Roboto-BlackItalic.ttf
├── Roboto-Bold.ttf
├── Roboto-BoldItalic.ttf
├── Roboto-Italic.ttf
├── Roboto-Light.ttf
├── Roboto-LightItalic.ttf
├── Roboto-Medium.ttf
├── Roboto-MediumItalic.ttf
├── Roboto-Regular.ttf
├── Roboto-Thin.ttf
├── Roboto-ThinItalic.ttf
├── RobotoCondensed-Bold.ttf
├── RobotoCondensed-BoldItalic.ttf
├── RobotoCondensed-Italic.ttf
├── RobotoCondensed-Light.ttf
├── RobotoCondensed-LightItalic.ttf
├── RobotoCondensed-Regular.ttf
├── SourceCodePro-Black.otf
├── SourceCodePro-BlackIt.otf
├── SourceCodePro-Bold.otf
├── SourceCodePro-BoldIt.otf
├── SourceCodePro-ExtraLight.otf
├── SourceCodePro-ExtraLightIt.otf
├── SourceCodePro-It.otf
├── SourceCodePro-Light.otf
├── SourceCodePro-LightIt.otf
├── SourceCodePro-Medium.otf
├── SourceCodePro-MediumIt.otf
├── SourceCodePro-Regular.otf
├── SourceCodePro-Semibold.otf
├── SourceCodePro-SemiboldIt.otf
├── SourceSerifPro-Black.otf
├── SourceSerifPro-Bold.otf
├── SourceSerifPro-ExtraLight.otf
├── SourceSerifPro-Light.otf
├── SourceSerifPro-Regular.otf
└── SourceSerifPro-Semibold.otf

0 directories, 47 files
```

### Generate PDF

Run

``` shell
$ make
```

to typeset and generate the PDF document. Or use your favorite GUI TeX
application, but choose `XeLaTeX` as the typeset engine to support the chinese
fonts.
# book-template-latex-ganx

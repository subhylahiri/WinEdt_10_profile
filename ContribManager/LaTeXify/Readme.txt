___________________________________________________________

 LaTeXify: TeXify+Biber items [for WinEdt 10]

===========================================================

 by Karl Koeller
 E-mail: karlkoeller@gmail.com

 http://www.winedt.org/

___________________________________________________________


WinEdt has support for automated compilations like TeXify and
PDFTeXify. However, if you want to change any of the default
engines, you have to go through WinEdt's configuration interfaces.
This package adds a few items to the TeX menu, giving the user the
chance to run an automated compilation by simply typing a shortcut
or pressing a toolbar button.

See USAGE for a list of items and related shortcuts.

---------------------------
 INSTALLATION
---------------------------

Open the macro file "Install.edt" in WinEdt, and execute it by
choosing "Macros" menu > "Execute Current Macro".

---------------------------
 UNINSTALLATION
---------------------------

Open the macro file "Uninstall.edt" in WinEdt (also available in
%b\Uninstall\LaTeXify folder), and execute it by choosing "Macros"
menu > "Execute Current Macro".

---------------------------
 USAGE
---------------------------

You can launch your automated compilation from the TeX menu or the
toolbar or typing one of the following shortcuts:

XeTeXify (runs BibTeX and PDFTeXify with XeLaTeX engine)
  Shortcut: Shift+Ctrl+E

LuaTeXify (runs BibTeX and PDFTeXify with LuaLaTeX engine)
  Shortcut: Shift+Ctrl+U

TeXify2PDF (runs BibTeX and TeXify+dvips+ps2pdf with LaTeX engine)
  Shortcut: Shift+Ctrl+Q

Biber (runs Biber)
  Shortcut: Ctrl+Alt+B

LaTeXify (runs Biber and TeXify with LaTeX engine)
  Shortcut: Ctrl+Alt+X

PDFLaTeXify (runs Biber and PDFTeXify with PDFLaTeX engine)
  Shortcut: Ctrl+Alt+P

XeLaTeXify (runs Biber and PDFTeXify with XeLaTeX engine)
  Shortcut: Ctrl+Alt+E

LuaLaTeXify (runs Biber and PDFTeXify with LuaLaTeX engine)
  Shortcut: Ctrl+Alt+U

LaTeXify2PDF (runs Biber and TeXify+dvips+ps2pdf with LaTeX engine)
  Shortcut: Ctrl+Alt+Q

# DBFZ BBS stuff for Notepad++

![preview](preview.png)

## BBS_BRO.xml

Custom syntax highlighting for dark n++ themes. Primarily *Deep Black*.

Requires my fork of [dobosken/bbscript](https://github.com/dobosken/bbscript) and it's associated .ron to work correctly.

`'Language' tab => 'User Defined Language' => Import.`

You might have to restart n++. If the theme doesn't automatically enable for .bbs files, select 'BBS_BRO' in the 'Language' tab manually while working on such a file.

## overrideMap.xml and bbs.xml

Custom BBS rules that enable the use of the 'Function List' panel.

This panel allows you to quickly get an overview, and navigate to the various States and Subroutines in your BBS file.

Simply drag and drop both .xml files into the 'functionList' directory found in your n++ installation directory (default: `C:\Program Files\Notepad++\functionList\`), then restart n++.

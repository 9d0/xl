# xl
xl imitates Microsoft Excel without shame. Currently it can only view very simple spreadsheets that are saved as tab-separated values. 

If you have Excel you can save your spreadsheet as a .tsv file which xl can read. If you don't have Excel you can use `xls2txt` on Plan 9 to extract tab-separated values from an .xls file.

If necessary, convert the character set to UTF-8 using `tcs`.

## Installation
xl is written in Lua and requires [lua9](https://github.com/telephil9/lua9).

## Synopsis
`% xl sheet`

The VGA font which is the default on 9front does not look great. You will get a nicer looking sheet using Tahoma or Lucida Sans:

`% font=/usr/k/lib/font/bit/tahoma/unicode.11.font xl sheet`

`% font=/lib/font/bit/lucidasans/unicode.7.font xl sheet`

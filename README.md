# unicode-samples
samples of unicode files in various formats.

The following file was taken from the original author, see
https://github.com/QbProg/unicode-samples :

- utf8.txt


Any other file was created from that file by me, converting
the original UTF8 file into Unicode code points and from that,
back into the most used Unicode variations.


Therefore, all this files contain identical code points.


These files have been created:

- utf8-bom.txt    (UTF8 with Byte Order Mark - byte by byte identical to original file)
- utf16le.txt     (UTF16 in little endian without Byte Order Mark)
- utf16le-bom.txt (UTF16 in little endian with Byte Order Mark)
- utf16be.txt     (UTF16 in big endian without Byte Order Mark)
- utf16be-bom.txt (UTF16 in big endian with Byte Order Mark)
- utf32le.txt     (UTF32 in little endian without Byte Order Mark)
- utf32le-bom.txt (UTF32 in little endian with Byte Order Mark)
- utf32be.txt     (UTF32 in big endian without Byte Order Mark)
- utf32be-bom.txt (UTF32 in big endian with Byte Order Mark)


'le'  stands for little endian
'be'  stands for big endian
'bom' stands for Byte Order Mark

Those files cover the most common unicode variations, and may
help to test unicode tools.

The original author didn't choose any license on his file,
so feel free to use it.

--wirbel

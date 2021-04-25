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

If any of this files is converted to UTF8 back again, the CRC32 using
0x04C11DB7 polynom should be 0x113CC8E0 for those files (any BOM skipped).

'le'  stands for little endian
'be'  stands for big endian
'bom' stands for Byte Order Mark

Those files cover the most common unicode variations, and may
help to test unicode tools.

The original author didn't choose any license on his file,
so feel free to use it.



Additionally, for testing of Unicode Encoding detection algorithms,
these files have been created by me:
- utf8-any-bom.txt
- utf8-any.txt
- utf16be-any-bom.txt
- utf16be-any.txt
- utf16le-any-bom.txt
- utf16le-any.txt
- utf32be-any-bom.txt
- utf32be-any.txt
- utf32le-any-bom.txt
- utf32le-any.txt

These files contain - in ascending order - the following Unicode code points:
- U+0020..U+007E (7bit ASCII, no control chars)
- U+0080..U+10FFFF, except
   - U+0A00  (no code point)
   - U+D800..U+DFFF (high/low surrogates)
   - U+FFFE..U+FFFF (no code point)
Every few chars, a newline '\n' is added for readability.
If those files are converted back to UTF8, the expected CRC32 is 0x926B6EAE.


--wirbel

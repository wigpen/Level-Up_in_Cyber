# Magic Bytes
## Otherwise Known as File Signatures

This is not my original work, this is someone elses probably, I can't remember if I did it, doesn't quite look like mine, but might be.

These are the first bytes of a file when you look at it in a Hex Viewer, you will find your own favourite hex viewer ... if you do not already have one.

Things to do
- Define a Hex Viewer
- List Hex Viewers
- Create a guide to installing and using them
- Links to external training



## File Signatures | 
 | Magic Bytes | What they mean |
 | ------ | ----- |
 | 01 06 01 00 | Job File | 
 | 1F 8B 08 | GZIP | 
 | 25 50 44 46 | PDF | 
 | 30 00 00 00 4C 66 4C 65 | EVT Event Viewer File | 
 | 50 4B 03 04 14 00 06 00 | Office | 
 | 50 4B 53 70 58 | PKSFX | 
 | 37 7A BC AF 27 1C | 7Zip | 
 | 46 75 6E 63 74 69 6F 6E | VBS | 
 | 42 5A 68 | BZip2 | 
 | 5F 27 A8 89 | JAR | 
 | FF D8 FF | JPEG | 
 | 50 4B 05 06 | PKZIP | 
 | 52 61 72 21 1A 07 | RAR | 
 | 57 69 6E 5A 69 70 | WinZIP | 
 | 72 65 67 66 | Registry Hive | 
 | 7B 5C 72 74 | RTF | 
 | 75 73 74 61 72 | TAR | 
 | D4 C3 B2 A1 | WINPCAP | 
 | A1 B2 C3 D4 | LIBPCAP | 
 | A1 B2 CD 34 | LIBPCAP | 
 | FF 4B 45 59 42 20 20 20 | SYS Keyboard Driver | 
 | FF FE 3C 00 3F 00 78 00 6D 00 6C | Windows At Job | 
 | 3C 3F 70 68 70 | PHP | 
 | 0D 44 4F 43 | DOC | 
 | FF D8 FF E0 | JPEG | 
 | 1F 8B 08 | GZIP | 
 | 23 20 44 69 73 6B 20 44 | VMDK | 
 | 30 00 00 00 4C 66 4C 65 | EVT | 
 | 45 6C 66 46 69 6C | EVTX | 
 | 41 45 53 | AESCrypt | 
 | 43 4F 57 44 | VMDK | 
 | 43 57 53 | SWF | 
 | 5A 57 53 | SWF | 
 | 46 57 53 | SWF | 
 | 46 49 4C 45 | NTFS MFT | 
 | 4A 41 52 43 53 00 | JARCS | 
 | 4B 44 4D | VMDK | 
 | 4C 00 00 00 01 14 02 00 | LNK | 
 | 4D 53 43 46 | CAB | 
 | 50 4B 03 04 | ZIP | 
 | 3C 3F 78 6D 6C | XML | 
 | 63 6F 6E 65 63 74 69 78 | VHD | 
 | D0 CF 11 E0 A1 B1 1A E1 | OLE | 
 | 40 65 63 68 | BATCH | 
 | 40 45 43 48 | BATCH | 
 | FF FE 90 02 01 00 | Trace Log File | 
 | 23 21 2F | UNIX SCRIPT | 
 | 4D 44 4D 50 | MDMP | 
 | FF FE 3C 00 25 00 | JSP | 
 | FE FF 00 3C 00 25 | JSP | 
 | 43 57 53 | CWS | 
 | 5A 57 53 | ZWS | 
 | 46 57 53 | FWS (Flash) | 
 | 30 3A 30 30 3A 30 30 | Log Relative | 
 | 7F 45 | ELF | 
 | 23 21 | Script | 
 | 1F 9D | TARZ | 
 | 1F A0 | TARZ | 
 | 3C 25 | JSP | 
 | 3C 25 40 | ASP | 
 | FF FE 3C 00 25 00 40 00 | ASP | 
 | FE FF 00 3C 00 25 00 40 | ASP | 
 | 4D 5A | EXE | 
 | FF FE | UTF16-Encoded File LE | 
 | FE FF | UTF16-Encoded File BE | 
 | CA FE | Java Class or DYLIB | 
  | ------ | ----- |
 | ### Special | 
  | ------ | ----- |
 | 5B 30 30 30 30 30 30 30 30 3A | MimiLSA Log | 
 | 5B 30 30 30 30 30 30 30 30 3A | MimiLSA Log | 
 | 65 63 68 6F | Batch | 
 | 40 65 63 68 6F | Batch | 
 | 5B 49 6E 74 | Internet Shortcut | 
 | FF FE 76 00 61 00 72 00 | Emotet JS | 
 | FF FE 56 00 65 00 72 00 73 00 69 00 6F | WER | 
 | 56 00 65 00 72 00 73 00 69 00 6F 00 6E | WER | 
 | 41 54 26 54 46 4F 52 4D | Gitlab EXIF | 
  | ------ | ----- |
 | ### APT | 
  | ------ | ----- |
 | 3C 62 6F 64 79 3E | Web | 
 | 4F 6E 20 45 72 72 6F 72 20 52 65 73 75 6D 65 | VBS | 
 | 3C 68 74 6D 6C | HTML | 
 | 3C 48 54 4D 4C | HTML | 
 | 2D 2D 2D 2D 2D 42 45 47 49 4E | Certificate PEM | 
 | 53 61 6C 74 65 64 5F 5F | OpenSSL Salted Format | 
 | 3C 25 2D 2D | JSP | 
  | ------ | ----- |
 | ### APT Extra | 
  | ------ | ----- |
 | 54 56 | Base64 EXE
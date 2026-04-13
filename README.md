# Metadata

| Picture        | Tools             | Link / Command       | Screenshot  | Analysis |
|----------------|-------------------|----------------------|-------------|----------|
| ocean.jpg|exiftool|https://exif.tools/exiftool|![image alt](https://github.com/Hafiz04/Metadata/blob/0ef0b3f8c3d69643cf11774664df955754241e64/exiftools.png)|A command-line tool that reads, writes, and edits metadata (hidden information) inside files—especially images.|
||exiftool in Kali|exiftool ocean.jpg|![image alt](https://github.com/Hafiz04/Metadata/blob/c544332d350f07768fedc5023250b61e1315e479/exiftool.kali.png)|also can see the flag in the comment section|
|Computer.jpg|Hexeditor|https://hexed.it/|![image alt](https://github.com/Hafiz04/Metadata/blob/0bf08ec40bbde7d8df23647631633f4b4cdbfdce/hexed.png)|raw binary data of computer.jpg interpreted as different number formats. The hex editor is showing you how those bytes can be read|
|dog.jpg|binwalk|binwalk dog.jpg <br>binwalk -e dog.jpg<br>cd _dog.jpg.extracted/|![image alt](https://github.com/Hafiz04/Metadata/blob/bef4e0208e95680c6c1b99c0610dbf2c1977c64e/binwalk.png)|a firmware analysis tool that scans files to find hidden/embedded files inside them|
|computer.jpg|strings|https://www.dcode.fr/strings-extractor|![image alt](https://github.com/Hafiz04/Metadata/blob/d4cb6796652b14504435dd777e841b141bc76728/string.png)|Extracts all readable text (strings) from a file, similar to the Linux strings command|
||Kali Linux|strings computer.jpg|![image alt](https://github.com/Hafiz04/Metadata/blob/3f3d2901ca76dab975a0bc860ba59ec0affff2a8/strings.kali.png)||
|solitaire.jpg|file|file solitaire.jpg|![image alt]()|the exe file is actually a PNG file|
|rubiks.jpg|file|file rubiks.jpg|![image alt]()|the jpg file is actually a PNG file|

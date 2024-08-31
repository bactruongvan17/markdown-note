# 1. Tar

### Summary 
- Abbreviation: **Tape Archive**
- Compression extension: **.tar**
- It was used primarily on UNIX and Linux system.
- It does not decrease files size in the folder, it only group files together.
- We use another tool with TAR to compress files like __Gzip (_.tar.gz_)__ or __BZip2 (_.tar.bz2_)__

### Commands

``` shell
- Compress file: `tar -cvf archive.tar /path/to/folder`
- Extract a TAR file:  `tar -xvf archive.tar`
- Compress with Gzip: `tar -cvzf archive.tar.gz /path/to/folder`
- Extract with Gzip: `tar -xvzf archive.tar.gz`
```
 
<br><br>

# 2. Zip

### Summary
- It is popular on Windows and other operating system.
- ZIP is both compress and group files in a single file.
- It decrease the file size.
- Each file the ZIP file is compressed individually.
- It is supported protecting with password for compression file.

### Commands

``` shell
- Compress a file: `zip archive.zip file1 file2 ...`
- Extract a .zip file: `unzip archive.zip`
- Compress a directory: `zip -r archive.zip /path/to/folder`
- Extract a file in a ZIP file: `unzip archive.zip file1`
```

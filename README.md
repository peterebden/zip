# zip
Fork of archive/zip from the Go stdlib, extended to support fast zipfile combining.

This is useful for the case where you need to read one or more zipfiles and write
them again without needing the decompressed content - for example, combining
multiple zipfiles into one.


Most of the code is forked from the Go standard library's [archive/zip](https://github.com/golang/go/tree/master/src/archive/zip) package.

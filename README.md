# PLZ
Update to Simple LZ Compression Code

Background:
Simple-LZ (SLZ) is a compression algorithm published by Adisak Pochanayon in 1993.
It is based on straight LZ77 'sliding windowed' with the addition of a simple tag extension that allows for higher compression (through longer match strings).
SLZ is a great tutorial or starting point for anyone interested in compression since the algorithm is very easy to understand.
A basic SLZ decompressor is only trivially more complicated than an RLE (Run-Length Encoding) compressor.
Also SLZ decompression can be made extremely fast for runtime -- on an optimized SLZ decompressor, highly compressed data can often be decompressed faster than a memcpy() for the same data.

$ ./mozlz4 --help
mozlz4 0.1.0
Justin Wong
Decompress and compress mozlz4 files. Overwrites existing files.

USAGE:
    mozlz4.exe [FLAGS] <input> [output]

FLAGS:
    -x, --extract     decompress mozlz4 (default)
    -z, --compress    compress to mozlz4
    -h, --help        Prints help information
    -V, --version     Prints version information

ARGS:
    <input>     input file, - for stdin
    <output>    output file, - for stdout (default)
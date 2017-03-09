# chunker
Command line tool to split a file into chunks of user-specified size, respecting delimitted breaks.

```bash
usage: chunker.py [-h] [-c CHUNKSIZE] (-d DELIMITER | -l LINES)
                  infile outfolder

Split input file into pieces.

positional arguments:
  infile                Path to input file.
  outfolder             Path to output folder.

optional arguments:
  -h, --help            show this help message and exit
  -c CHUNKSIZE, --chunksize CHUNKSIZE
                        Approximate size of file chunks.
  -d DELIMITER, --delimiter DELIMITER
                        Delimiter for preserving text groups.
  -l LINES, --lines LINES
                        Number of lines to be considered a text group.
```

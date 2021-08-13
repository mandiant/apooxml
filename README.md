# apooxml
Generate YARA rules for OOXML documents using ZIP local header metadata. To learn more about this tool and the methodology behind it, check out the accompanying blog [here](https://www.fireeye.com/blog/threat-research/2021/08/detecting-embedded-content-in-ooxml-documents.html).

## Usage
```
➜ python3 apooxml.py -h
usage: apooxml.py [-h] [-a AUTHOR] [-n NAME] [-o OUT] sample

Generate YARA rules for OOXML documents.

positional arguments:
  sample                OOXML document to generate YARA rule from.

optional arguments:
  -h, --help            show this help message and exit
  -a AUTHOR, --author AUTHOR
                        YARA rule author.
  -n NAME, --name NAME  YARA rule name.
  -o OUT, --out OUT     YARA rule file name.
```

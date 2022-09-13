# TTParser
little python script to convert json TTPs layer to txt file

```
usage: parser.py [-h] [--text TEXT] layer

Convert json att&ck layer to simple text

positional arguments:
  layer        Path to existing json layer

options:
  -h, --help   show this help message and exit
  --text TEXT  Path to a new description file
```

Example: 

`python test.py layer.json --text data.txt`


# torrent2magnet
A very simple Python 3 utility for converting .torrent files to magnet links

## Requirements
This script requires Python 3 and depends on:
* [hashlib](https://docs.python.org/3/library/hashlib.html)
* [base64](https://docs.python.org/3.1/library/base64.html)
* [bencodepy](https://github.com/eweast/BencodePy)

## Usage
Suppose that your Python 3 interpreter is ``python`` and that the torrent file you want to convert is located at ``/path/to/my/file.torrent``, then you can get your magnet link by simply running:
```bash
python torrent2magnet.py /path/to/my/file.torrent
```

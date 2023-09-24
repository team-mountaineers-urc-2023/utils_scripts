# Collection of useful scripts

## Extract text from images (text-extract)

### Installation Instruction

```bash
# install python requirements
pip install pytesseract pyperclip
# install tesseract
sudo apt install tesseract-ocr
```

### Simple Usage: 
```bash
# call with only image argument
text-extract example.png
```

```bash
# see all parameters and their usage
text-extract --help
```

## Slow vcs pull (svcsp)


### Installation Instruction

```bash
# install python requirements
pip install gitpython
```


### Simple Usage:
```bash
# just running the script will execute with default args in ~/workspace-wanderer/src
svcsp
```

```bash
# see all arguments
svcsp --help
```
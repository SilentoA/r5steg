# r5steg
Text in text steganography program using zero width space characters.

# Usage
- Make sure you meet all the [requirements](https://github.com/byru55o/r5steg#requirements), if not install them with [**pip**](https://pypi.org/project/pip/)  
- Execute `main.py`: `python3 main.py`


# Under development
This piece of free software is currently on BETA phase, feel free to report any bugs or contribute with a PR!
### To do list:
- Support decoding multiple messages at once [DONE]
- Add compression (maybe using trinary, quaternary, or more bases instead of binary)
- Add encryption with passwords
### ZW characters used:
characters to be used in the future are marked with [*]
- `U+200C \xe2\x80\x8c	ZERO WIDTH NON-JOINER` for ' '
- `U+2060 \xe2\x81\xa0	WORD JOINER` for '0'
- `U+200B \xe2\x80\x8b	ZERO WIDTH SPACE` for '1'
- *`U+200D \xe2\x80\x8d	ZERO WIDTH JOINER` for '2'
- *`U+200E \xe2\x80\x8e	LEFT-TO-RIGHT MARK` for '3'
- *`U+200F \xe2\x80\x8f	RIGHT-TO-LEFT MARK` for '4'
- *`U+2028 \xe2\x80\xa8 LINE SEPARATOR` for '5'
- *`U+2029 \xe2\x80\xa9 PARAGRAPH SEPARATOR` for '6'
- `U+FEFF \xef\xbb\xbf  ZERO WIDTH NO-BREAK SPACE` for wrapping
### Feedback
Im up to any kind of feedback!

# Requirements
- **Python 3** (3.10.8 was used but should work with any) 
- [**pyperclip**](https://pyperclip.readthedocs.io/en/latest/) for auto copy-to-clipboard. 
- [**readline**](https://docs.python.org/3/library/readline.html) for input usability.

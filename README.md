# b3DS
A 3DS/New 3DS Rom Decryptor and Encrypter

### If anyone wants to improve on the code, feel free to do so.

## Prerequisites
* Python 3.11+
* pip
* pycryptodome

## Installation
After you've installed the latest version of Python 2, run `pip install pycryptodome` in command prompt.

## Usage
python {b3DSEncrypt.py|b3DSDecrypt.py} "File location of rom" eg. '~/dox/games/emulator/nintendo/3ds/3DS0033 - The Legend of Zelda Ocarina of Time 3D (U).3ds'

## Status
Supports all known crypto-types: 

* Normal (Key 0x2C)
* 7.x (Key 0x25)
* New3DS 9.3 (Key 0x18)
* New3DS 9.6 (Key 0x1B)

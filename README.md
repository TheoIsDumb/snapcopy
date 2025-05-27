# snapcopy


https://github.com/user-attachments/assets/044ccb7e-14a6-4fd7-a7c0-3c4420494d78

a lil script that screenshots text, runs tesseract OCR and performs a browser search.   
maybe something like this already exists, but i don't care.

## installation

```
git clone git@github.com:theoisdumb/snapcopy.git
cd snapcopy
sudo mv snapcopy /usr/bin # bruh
```

## note

used to use flameshot/import, but apparently screenshotting can't be aborted when import is used, and while flameshot does allow it, it returns 0 as $?. therefore switched to maim.

## dependencies

- [maim](https://github.com/naelstrof/maim)
- [tesseract](https://github.com/tesseract-ocr/tesseract)
- tesseract-data-eng (acc. to arch repos)

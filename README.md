# snapcopy


https://github.com/user-attachments/assets/044ccb7e-14a6-4fd7-a7c0-3c4420494d78

a lil script that screenshots text, runs tesseract OCR and ~~copies text to clipboard~~ performs a browser search.   
maybe something like this already exists, but i don't care.

## installation

```
git clone git@github.com:theoisdumb/snapcopy.git
cd snapcopy
sudo mv snapcopy /usr/bin # bruh
```

## note

flameshot is used for screenshotting, but you can use `import` from imagemagick. just open the script, uncomment line 4 and comment line 3.

## dependencies

- [flameshot](https://flameshot.org/)
- [tesseract](https://github.com/tesseract-ocr/tesseract)
- tesseract-data-eng (acc. to arch repos)
- [xclip](https://github.com/astrand/xclip)

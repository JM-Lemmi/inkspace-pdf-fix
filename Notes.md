# Wacom Inkspace broken PDFs Troubleshooting

## pdf stream decoding

its not svg, but seems to be very close to it.

I still dont understand the encoding. deleting parts does not really seem to work, though I wonder if I could do it.

### Stevens PDF-parser

using [pdf-parser by dider stevens](https://blog.didierstevens.com/programs/pdf-tools/) from [stackoverflow](https://stackoverflow.com/questions/27997930/how-to-decode-a-pdf-stream)

```
python '.\format troubleshooting\pdf-parser.py' -o 4 -f -d '.\format troubleshooting\obj4.dump' '.\original files\WCM0001.pdf'
```

output to obj4.dump

### Itext rups

https://github.com/itext/rups/releases/tag/5.5.9

the software also does some nice stuff

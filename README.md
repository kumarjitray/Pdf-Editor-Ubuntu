# Pdf-Editor-Ubuntu
It is not developed by me. I am just keeping it for Ubuntu users.

## Software
### install
``` sudo apt install pdfarranger```

## To format PDF size
### install
```sudo apt install ghostscript```
### Then Run
```gs -o output.pdf -sPAPERSIZE=a4 -dFIXEDMEDIA -dPDFFitPage -dCompatibilityLevel=1.4 -sDEVICE=pdfwrite input.pdf```

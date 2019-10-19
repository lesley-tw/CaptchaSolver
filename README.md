# JDownloader 2 Offline Captcha solver
This Tool automatically solves Captchas for you! JDownloader already solves a lot of captchas on its own, but for some hosts you have to input the result by hand. This tool reduces the list of unsupported hosts. Full [List of supported Captachs by JD2 here](https://board.jdownloader.org/showthread.php?p=225515)

This tool is running in NodeJs with [JIMP](https://github.com/oliver-moran/jimp) for image processing and [tesseract.js ](https://github.com/naptha/tesseract.js) for OCR

## Installation Windows, Linux (Beta), Mac (Untested)
1. Download the latest standalone zip: [win](https://github.com/cracker0dks/CaptchaSolver/releases/download/untagged-7d1f90fd4b27d2602ed5/CaptchaSolver-1.4.3_standalone_win.zip) OR [linux & mac](https://github.com/cracker0dks/CaptchaSolver/releases/download/untagged-747e930d6644213e0ab1/CaptchaSolver-1.4.3_standalone_linux.zip)
2. Extract the "JDownloader 2.0" content in your current JD2 folder
3. restart JD2 and start downloading

## Supported Types of Captchas
This is a list of supported Captchas and the hosts, I know, are using them.
### 6 Digits Captcha
![ks](/docs/ksinput.gif)

Known Hosts with this captcha:
* keep2share.cc
* fileboom.me

Docu on how I solve this Captcha type: [HERE](docs/howToSolve6DigitCaptchasWalkthrough.md)

### 4 Digits Captcha
![ks](/docs/xFQIX.png)

Known Hosts with this captcha:
* przeklej.org

Docu on how I solved this Captcha type: [HERE](docs/howToSolve4DigitCaptchasWalkthrough.md)

---------------------

Thanks to [budel](https://github.com/budel) for the linux part!


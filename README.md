<h1 align="center">™✔ (Python) Desktop Watermarking App</h1>
<p align="center">
  <img alt="Language" src="https://img.shields.io/badge/language-python-blue"><br>
  <img alt="Python Version" src="https://img.shields.io/badge/python_version-3.11-yellow" /><br>
  <img alt="Version" src="https://img.shields.io/badge/app_version-1.10-blue.svg?cacheSeconds=2592000" />
  <p align="center">
  <a href="https://twitter.com/rhc_iv" target="_blank">
    <img alt="Twitter: rhc_iv" src="https://img.shields.io/twitter/follow/rhc_iv.svg?style=social" /><br>
  </a>
  <a href="https://mastodon.social/@rhciv1972" target="_blank">
    <img alt="Mastodon: rhciv1972" src="https://img.shields.io/mastodon/follow/109497169591319512?domain=https%3A%2F%2Fmastodon.social&style=social" />
  </a>
  </p>
</p>

### 🛋️ [Homepage](https://github.com/rhc-iv/py-watermark-app)
---
> Desktop application made with Python to watermark personal images.

<p align="center">
  <img alt="Image Watermarking App" src="https://github.com/rhc-iv/py-watermark-app/blob/main/screenshot.png" width="800" height="600" />
</p>

## Usage

- Open and run `main.py` in the editor/IDE of your choice.
- _**Browse**_ to open a file dialog frow image browsing on your computer.
- _**Cancel**_ to cancel the operation and return to the main app GUI.
- _**Close**_ to exit the app.
- Simply select _**Browse**_ if you want to watermark subsequent images. No need to re-run the app for each image.

## 🗒️ Notes

- The `images` folder contains 2 files:
  - An app logo image (`logo.png`)
  - A watermark image (`wm_rhc.png`)
- These images should be replaced with your own and placed in a directory named `images` in the same directory as `main.py`. The `logo.png` isn't necessary for the app to work.
- By default, the image you choose as your watermark will be placed in the upper-left corner of the image that you are watermarking.
- Once selected from the file browser, your image will be watermarked instantly. It will be saved, by default, to the `images` directory with `wmrk` prepended to the original file name.
- The input, output, and intial directory (for the file browser) can be edited in `main.py`.

## 📝 To-Do

- (Personal) Improve logo
- Write function(s) to watermark multiple images simultaneously.
- Write function to allow selection of watermark location on image via GUI.

## 👤 Author

**Robert H. Carr, IV**

* Twitter: [@rhc_iv](https://twitter.com/rhc_iv)
* Github: [@rhc-iv](https://github.com/rhc-iv)
* Mastodon: [@rhciv1972](https://mastodon.social/@rhciv1972)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/rhc-iv/py-watermark-app/issues). 

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_

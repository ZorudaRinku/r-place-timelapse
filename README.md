# r-place-timelapse

---
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
## About

---
This is a script to create a timelapse video from an archive of /r/Place (https://www.reddit.com/r/place/).

## Features

---
* Crop /r/Place images to custom bounds to select a region of interest.
* Upscales images to HD and packs them into a timelapse of custom length.
* Creates H264 .mp4 video.
* Automatically download archive images from zevs.me r/place archive and unpack them.
* Automatically download h264 codec from Cisco.

[![/r/KickOpenTheDoor](https://cdn.discordapp.com/attachments/777290393544818718/960954482211029043/kick-open-the-door.gif)](https://www.reddit.com/r/KickOpenTheDoor)

## Requirements

---
* [Latest Version of Python 3](https://www.python.org/downloads/)
* Install requirements with `pip install -r requirements.txt`
* Currently, only supports Windows

## Usage

---
Run the script with `python3 main.py`

Script will prompt for the following:

* Downloading h264 codec from Cisco Github repo (Automatic optional)
    * If no, place `openh264-1.8.0-win32.dll` or `openh264-1.8.0-win64.dll` into script directory
* Downloading archive images from zevs.me r/place archive (Automatic optional)
    * If no, place `.png` images in `images/` directory
* Coordinates of the region of interest
* Image upscale factor
* Timelapse length

Output file: final.mp4

---
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/zorudarinku)

https://ko-fi.com/zorudarinku

BTC: 3BkFBBQNTwsu7vw1HyeuZXtosqBgUWKTJt

ETH: 0x0c369d797740C516d0eb7736C901862C558Fe8Af
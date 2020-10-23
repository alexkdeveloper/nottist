# Nottist 

![screenshot.png](/data/screenshot.png)

Application for creating notes. The application allows you to create, edit and delete unwanted notes.

## Get it from the elementary OS AppCenter!

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/nottist)

This app is available on the elementary OS AppCenter.

# Install it from source

You can of course download and install this app from source.

## Dependencies

Ensure you have these dependencies installed

* granite
* gtk+-3.0
* switchboard-2.0

## Install, build and run

```bash
# install elementary-sdk, meson and ninja 
sudo apt install elementary-sdk meson ninja
# clone repository
git clone {{repository_url}} nottist
# cd to dir
cd nottist
# run meson
meson build --prefix=/usr
# cd to build, build and test
cd build
sudo ninja install && nottist
...

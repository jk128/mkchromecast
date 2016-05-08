---
title: "Install"
bg: orange
color: black
fa-icon: toggle-on
---

## Mac OS X app

[Download the DMG](#download), and drag **mkchromecast** to your
`/Applications/` folder.  Note that for the moments `node` is the only backend
supported. You also need to install Soundflower as shown below.

### Soundflower (Mac users only)

For Soundflower you can check
[https://github.com/mattingalls/Soundflower/](https://github.com/mattingalls/Soundflower/)
or if you have [Homebrew](http://brew.sh/) you can use [brew
cask](https://caskroom.github.io/) as follows:

``
brew cask install soundflower
``

Or just download the [latest dmg
file](https://github.com/mattingalls/Soundflower/releases).`

-------------------------

## Linux based installation

More information soon.

-------------------------

## Installing from Github

To install **mkchromecast**, clone this repository:

```
git clone https://github.com/muammar/mkchromecast.git
```

Or you may download one of the [stable releases
here](https://github.com/muammar/mkchromecast/releases), and unzip the file.

#### Python

To install the python requirements use the `requirements.txt` file shipped in
this repository:

```
pip install -r requirements.txt
```

**Note**: if this step fails, maybe you need to run the installation with
`sudo` as shown below. However, before installing using this method verify why
a regular user cannot install the requirements.

```
sudo pip install -r requirements.txt
```

**Linux** users can try to install these python requirements using the package
managers coming with their distributions.

Now you are good to go!. If you are interested in installing ffmpeg, please
[follow the instructions here](https://github.com/muammar/mkchromecast/#ffmpeg).
# Descendant Device Specific

## Dependencies
Before getting started, please be sure to have the following packages in your OS:

```bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev openjdk-8-jdk libwxgtk3.0-dev```

## Init our repo
To start your own descendance, begin with:

```repo init -u https://github.com/DescendantDeviceSpecific/manifest.git -b TwoDotTwo_staging```

Then sync it up with:

```repo sync --force-sync --no-clone-bundle -j$(nproc --all)```

## Sync your device repositories

We've stored them for you [here](https://github.com/descendant-devices), if your device isn't listed, check the paragraph "Contributing".

## Get at work 
To begin your build please do as follows:

```. build/envsetup.sh 
lunch descendant_codename-buildtype
mka bacon
```
## Contributing 
We do appreciate contributions to our source. 

In any form. 

If you're considering to contribute, please head to our Telegram chat

([click to visit Descendant website](https://descendant.me/) to find it out) or just PR the necessary commits over my repos.

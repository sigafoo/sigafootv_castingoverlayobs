# sigafoo.tv obs casting overlay

Howdy, I'm sigafoo. I've been casting in tf2 for over three years now and have started doing my own production work about a half year ago. I realized that there wasn't a lot of resources on how to cast... do camera... production... anything. I'm trying to make a base that is customizable and easy for people to start up their own production.

Also check out http://sigafoo.tv/casting for more casting help

### Prerequisities

* OBS Classic: https://obsproject.com/
* CLR Plugin for obs classic: https://obsproject.com/forum/resources/clr-browser-source-plugin.22/
* Video source plugin for obs classic: https://obsproject.com/forum/resources/video-source-plugin.20/
* NotePad++: https://notepad-plus-plus.org/ (not required, but better than editing with textpad)

```
NOTE: You definitely can use obs studios, but you'll have to manually build the scenes.
```


### Getting it working

```
NOTE: The files don't actually need to be in this exact folder. 
This is purely so that if you are using my config for obs classic. 
You won't have to change any of the clr properties to have it work initially.
```

Download the zip of this repository and extract the files to "c:\tf2camera"

So it should look like: 

C:\tf2camera\PerGamePics

C:\tf2camera\StaticPictures


If you are using OBS Classic, open it up

```
Make sure you back up any scenes you currently use by exporting them. 
Scene Collection > Export
```

Import the \obsconfig\DefaultCameraConfig.xconfig into obs classic

Scene Collection > Import

That's it.

### Give it a test

Underneath "Scenes" select: Waiting_Prior_Background

Click on "Preview Stream" and you should see everything working.

# Customize your cast

Open up the \PerGamePics\htmlpages\SetupFile.json

```
NOTE: If you have OBS running and you change something in the json file.
IT WILL NOT AUTOMATICALLY UPDATE THE PAGE. In order to update the page,
either restart the preview or force refresh the clr source. 

The easiest way I've found to do this is to right click on the source > properties
Change the Opacity very slighty and click OK. This should refresh the page.
```

## Authors

* **Derek Sigafoo** - http://twitch.tv/sigafoo

## Acknowledgments

* Thanks to Jon from BlackOutGamingTV for helping me out with random questions when I was starting up in doing production.
* Also thanks to eXtine for letting jump in casting for the first time way back 2013


---
title: RokBox
tags: [rokbox, index, foobar]

---

Introduction
-----

RokBox2 is a fully responsive modal plugin for Joomla and the successor of the very popular but quite dated RokBox1. Rewritten from the ground up it can display many different media formats such as images, videos, music, embedded widgets, Ajax content and Joomla modules and takes advantage of the new technologies such as HTML5 and CSS3.

![][featured]

RokBox2 is bundled with:

1. Content plugin
2. Editor Button plugin
3. System plugin

The **Content** plugin can auto-generate thumbnails of local images that can be used as content for the RokBox2 links. All thumbnails generated are responsive so that they can easily adapt to any device.

The **Button** plugin enables the RokBox Editor Button which allows for easy creation of RokBox2 snippets with just a few clicks.

The **System** plugin is responsible for loading the assets necessary for RokBox2 to work.

>> NOTE: If you are upgrading from RokBox1 and you are using the old RokBox syntax, such as `{rokbox}` or `<a rel="rokbox" ..`, you can enable the Backward Compatibility from both the **System** and **Content** plugin.
>>
>> Be aware that the Backward compatibility can dramatically slow down the loading of your site. It is highly suggested to convert the old syntax into the new one.

Requirements
------------

RokBox2 has the following requirements in order to operate:

* Joomla 3.x - ensure you are using the latest version
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.


Key Features
------------

* HTML5 and CSS3
* Fully Responsive
* Auto thumbnails generator
* Captions supporting HTML syntax
* Ajax Content listener
* Multiple media types supported:
    * Images: base64 encoded, jpg, gif, png, bmp, webp
    * HTML5 Video and Audio
    * TwitPic
    * Instagram
    * YouTube
    * Vimeo
    * Telly (ex TwitVid)
    * Metacafe
    * Dailymotion
    * Spotify
    * Google Maps
* Fit/Unfit Screen: If an image is too big it gets shrunk to fit the view-port but you can always click the Fit Screen icon to expand it and scroll.
* Albums to group related images
* Key Bindings for easy navigation: `⇠` (Previous), `⇢` (Next), `f` Fitscreen/Unfitscreen, `esc` Close


How to install
--------------

Installing RokBox2 takes just a matter of few minutes.

The first thing you will need to do is [download][download] the latest version of RokBox2. The package you will download is a bundle containing all of the required plugins to get RokBox2 up and running and it is compatible with Joomla 3.x. It does not need to be uncompressed.

Once you have downloaded the package, go into the Joomla Administrator and:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokbox-2.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

If everything worked properly you will get a success message notification. You can customize both plugins accessing from: `Extensions -> Plugin Manager`, where they are listed as **Content - RokBox** and **System - RokBox**.

>> NOTE: RocketTheme packages do not require you to first uninstall and then install again. You can simply install and the package will determine if it requires to update your currently installed RokBox (whether it is RokBox1 or RokBox2) or if it requires to just install it.


[featured]: assets/rokbox2-layout.png
[download]: https://rockettheme.com/extensions-downloads/free/rokbox/3173-rokbox-plugin/download

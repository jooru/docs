---
title: RokWeather
description: Your Guide to Using RokWeather for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!rokweather:RokWeather

---

Introduction
-----
![][rokweather]
RokWeather is an Ajax-powered weather module which utilizes the Yahoo or Wunderground APIs to display weather data and related information from regions all across the globe.

Included are options to display temperature, climate, wind speed as well as frontend based location user interaction, default location settings and cookie enabling options.

Requirements
------------
RokWeather has the following requirements in order to operate:

* Joomla 3.x - ensure you are using the latest version
* Compatible Browsers: Firefox, Chrome, Safari, IE8+, Opera.

>> NOTE: Internet Explorer 11+ and Edge are supported, but versions 8, 9, and 10 are no longer supported by Microsoft and while they may work, are not recommended.

Key Features
------------
* **Graphical Representation**: the module is packaged with images to showcase all types of weather from rain to sunshine
* **Location Chooser**: click the current area and type your desired location and the module will show the appropriate weather, with both frontend and backend configuration options
* **Temperature Units**: RokWeather has support for both the Fahrenheit and Celsius temperature scales
* **Forecast**: Up to 4 days worth of weather forecast (Maximum of 2 for Yahoo)
* **Multiple Readings**: optional parameters to show humidity, wind speed and weather descriptions
* **Cookie Control**: Options to configure whether a user's location is stored via a cookie or refreshed each time

>> The Google API has been replaced by Yahoo and Wunderground.  Also, if you experience the Fatal error: Call to undefined function `curl_init()` error then you need to have CURL enabled on your server. You can ask your hosting provider to activate this.

How to install
--------------
Installing RokWeather takes just a matter of few minutes.

The first thing you’ll need to do is [download][download] the latest version of RokWeather. The package you will download contains everything to get RokWeather up and running and it is compatible with Joomla 3.x. It does not need to be uncompressed. 

Once you have downloaded the package, go into the Joomla Administrator and:

From Joomla 3.x:

* Select from the top menu: `Extensions -> Extension Manager -> Install`
* Click on Upload Package File **Choose File** button
* Select the `rokweather.zip` that you just downloaded from your local drive.
* Click the **Upload & Install** button.

>> NOTE: For additional information on installing extensions, visit our detailed extensions installation guide located [here][install].

If everything worked properly, you will get a notification indicating as much.

>> NOTE: RocketTheme packages **do not** require you to uninstall them prior to updating or adding new associated extensions. You can simply install and the package will determine if it requires to update your currently installed RocketTheme extensions.

[featured]: assets/roksprocket-layout.jpeg
[download]: https://rockettheme.com/extensions-downloads/club/1003-rokweather
[install]: ../../platform/extensions.md#how-to-install-an-extension
[rokweather]: assets/rokweather.jpeg
[details]: assets/rokweather_details.jpeg

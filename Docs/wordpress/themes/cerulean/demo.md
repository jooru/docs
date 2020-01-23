---
title: Cerulean: Recreating the Demo
description: Your Guide to Recreating Elements of the Cerulean Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/cerulean:Cerulean

---

Introduction
-----

![][theme2]

Recreating features of the demo site used to show off some of the more interesting aspects of Cerulean can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Cerulean theme.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Cerulean:

* [Gantry Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* [RokCommon Library](http://www.rockettheme.com/wordpress/plugins/rokutilities) (Should be Installed and Activated Before RokGallery and/or RokSprocket)
* [RokSprocket][roksprocket]
* [RokGallery][gallery]

All of these plugins are included with the Cerulean RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Cerulean demo sits apart from the rest of the page layouts in that it features the latest and greatest features used in the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Cerulean theme.

Theme Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a setting override. This can be done by navigating to **Administrative Dashboard -> Cerulean Theme** and selecting the **+** icon located just above the **Style** settings tab. 

It would be a good idea for organization to name this layout override something like **Front Page** as it would be used only for the front page of your site.

#### Assignments
The next step you will need to take in creating your Theme Settings override is to assign the Front Page override to the site's home page. Under the **Theme Page Types** list, you will want to select both **Home Page** and **Front Page**. These settings can be found by navigating to **Assignments > Theme Page Types** in the theme settings.

Doing this will assign the override to these two page types. This will allow the override to cover all access scenarios that would lead a user to your site's main home page.

>> Under the administrative area, you can check you site's home page settings by navigating to **Settings -> Reading** and making sure that **Your latest posts** is selected. This is the setting we use for the demo content's home page as it does not require the creation of a static page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [override portion][demooverride] of this tutorial.

Widget Settings
-----
![][cerulean]

:   1. **Top - Logo** [6%, 17%, se]
    2. **Top - Gantry Login Form** [6%, 80%, sw]
    3. **Header - Gantry Menu** [9%, 58%, sw]
    4. **Slideshow - RokGallery Slideshow** [13%, 17%, se]
    5. **Sidebar - Recent News** [27%, 45%, se]
    6. **Sidebar - Search Our Site** [22%, 82%, sw]
    7. **Sidebar - About Cerulean** [28%, 82%, sw]
    8. **Sidebar - Gantry Extras** [44%, 82%, sw]
    9. **Sidebar - Cerulean Demo** [60%, 82%, sw]
    10. **Footer - Demo Info** [77%, 17%, se]
    11. **Footer - Top Features** [77%, 40%, se]
    12. **Footer - Contact Us** [77%, 62%, se]
    13. **Copyright - Gantry Copyright** [91%, 18%, se]
    14. **Copyright - Gantry To Top** [91%, 78%, sw]

Like any of our Gantry theme demos, Cerulean utilizes widget overrides to allow different widget placements for various areas of your WordPress site. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the widget placement and settings for the various widget positions as they appear in the Front Page widget override. Not all of these positions were overwritten. Some positions (such as the Header section) are often set in the primary default widget setting.

One important thing to note here is that many of the widget sections included in our demo are split up using a **Gantry Divider** widget. This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section. You will see the Gantry Divider in any widget section breakdowns as they are included in the demo.

### Widget Sections

* [Top][top]
* [Header][header]
* [Slideshow][slideshow]
* [Sidebar][sidebar]
* [Footer][footer]
* [Copyright][copyright]

[gantry]: http://gantry.org/downloads
[rokajaxsearch]: http://www.rockettheme.com/wordpress/plugins/rokajaxsearch
[rokbox]: http://www.rockettheme.com/wordpress/plugins/rokbox
[roksprocket]: http://www.rockettheme.com/wordpress/plugins/roksprocket
[cerulean]: assets/cerulean.jpeg
[theme2]: assets/cerulean2.jpeg
[roksprocket]: ../../plugins/roksprocket/
[gallery]: http://www.rockettheme.com/wordpress/plugins/rokgallery
[faq]: faq.md
[menu]: ../../start/menu.md
[override]: http://docs.gantry.org/gantry4/configure
[slideshow]: demo_slideshow.md
[feature]: demo_feature.md
[sidebar]: demo_sidebar.md
[footer]: demo_footer.md
[header]: demo_header.md
[top]: demo_top.md
[copyright]: demo_copyright.md
[demooverride]: demo_override.md

---
title: Protean: Recreating the Demo
description: Your Guide to Recreating Elements of the Protean Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/protean:Protean

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Protean can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Protean Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particles as they appear on the front page of our demo. These can all be found and edited via Templates > Protean - Home > Layout.

![](assets/protean2.jpg)

:   1. **Navigation** Logo (Particle) [1%, 15%, se]
    2. **Navigation** Menu (Particle) [1%, 55%, se]
    3. **Slideshow** Own Carousel (Particle) [4%, 10%, se]
    4. **Above** Simple Content (Particle) [17%, 25%, se]
    5. **Above** Content Array (Particle) [19%, 10%, se]
    6. **Feature** Simple Content (Particle) [27%, 30% se]
    7. **Feature** Content Tabs (Particle) [30%, 15%, se]
    8. **Expanded** Flipster (Particle) [41%, 2%, se]
    9. **Expanded** Info List (Particle) [53%, 10%, se]
    10. **Extension** Owl Carousel (Particle) [62%, 15%, se]
    11. **Bottom** Info List (Particle) [72%, 12%, se]
    12. **Footer** Image Grid (Particle) [78%, 2%, se]
    13. **Footer** Simple Content (Particle) [90%, 22%, se]
    14. **Footer** Newsletter (Particle) [92%, 35%, se]
    15. **Copyright** Simple Menu (Particle) [97%, 30%, se]
    16. **Copyright** Branding (Particle) [98%, 50%, se]
    17. **Copyright** Social (Particle) [98%, 85%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Protean, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Templates > Protean - Home > Layout. Any additional particles that are found in the Subpages of our Protean RocketLauncher can be located via your Joomla Administrator > Extensions > Modules. Joomla allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

* Template Particles
    * [Owl Carousel](particle_owl.md)
    * [Video and Video Grid](particle_video.md)
    * [Event List](particle_event.md)
    * [Pricing Table](particle_pricing.md)
    * [Joomla Articles](particle_joomla.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Grid Statistic](particle_grid.md)
    * [Content Tabs](particle_tabs.md)
    * [Simple Content](particle_simple.md)
    * [Image Grid](particle_image.md)
    * [Simple Weather](particle_weather.md)
    * [Swiper](particle_swiper.md)

* Core Particles 
    * [Logo](http://docs.gantry.org/gantry5/particles/logo)
    * [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    * [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    * [Social](http://docs.gantry.org/gantry5/particles/social)
    * [Module Positions](http://docs.gantry.org/gantry5/particles/position)
    * [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    * [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    * [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    * [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
    * [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    * [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Social](http://docs.gantry.org/gantry5/particles/social)
* [Module Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Protean:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Protean RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Protean demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Protean demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpg)

In order to make it really easy to replicate the home page, we included a convenient layout preset that enables you to load the home page as it is found in our demo. This preset is called **Home - Particles** (included in the standalone package) and it includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout. If you downloaded the theme and not a RocketLauncher, this is the best option for you if you want a copy of the front page with minimal effort.

You can access this preset by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpg)

Protean has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Protean > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Protean** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.

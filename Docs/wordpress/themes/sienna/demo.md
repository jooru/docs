---
title: Sienna: Recreating the Demo
description: Your Guide to Recreating Elements of the Sienna Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/sienna:Sienna

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Sienna can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Sienna Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the WordPress back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Widget and Particle Settings
-----

Below, you will find the widget placement and settings for the various widget positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/sienna2.jpg)

:   1. **Navigation Main** Logo (Particle) [2%, 10%, se]
    2. **Navigation Main** Menu (Particle) [2%, 55%, se]
    3. **Header Main** Owl Carousel (Particle) [5%, 7%, se]
    4. **Showcase Main** Booking Form (Particle) [13%, 7%, se]
    5. **Slideshow Main** Image Grid (Particle) [21%, 1%, se]
    6. **Feature Main** Simple Content (Particle) [28%, 35% se]
    8. **Feature Main** Simple Content (Particle) [33%, 10%, se]
    8. **Feature Main** Image Grid (Particle) [33%, 35%, se]
    9. **Feature Main** Simple Menu (Particle) [51%, 22%, se]
    10. **Expanded Main** Simple Content (Particle) [56%, 35%, se]
    11. **Expanded Main** Simple Booking (Particle) [62%, 10%, se]
    12. **Footer Main** Owl Carousel (Particle) [82%, 13%, se]
    13. **Copyright Main** Simple Weather (Particle) [90%, 12%, se]
    14. **Copyright Main** Newsletter (Particle) [90%, 36%, se]
    15. **Copyright Main** Social (Particle) [90%, 70%, se]
    16. **Copyright Main** Simple Menu (Particle) [94%, 12%, se]
    17. **Copyright Main** Simple Menu (Particle) [94%, 23%, se]
    18. **Copyright Main** Simple Menu (Particle) [94%, 36%, se]
    18. **Copyright Main** Simple Menu (Particle) [94%, 50%, se]
    19. **Copyright Main** Simple Content (Particle) [94%, 65%, se]
    20. **Copyright Main** Copyright (Particle) [98%, 34%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Sienna, as well as links to documentation to help you get started:

* Theme Particles
    * [Owl Carousel](particle_owl.md)
    * [Booking Form](particle_booking.md)
    * [Simple Booking](particle_simplebooking.md)
    * [Simple Menu](particle_simplemenu.md)
    * [Simple Weather](particle_weather.md)
    * [BookBlock](particle_book.md)
    * [WordPress Posts](particle_wordpress.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Grid Statistic](particle_grid.md)
    * [Simple Content](particle_simple.md)
    * [Image Grid](particle_image.md)
    * [Swiper](particle_swiper.md)
* Core Particles (Documented on [Gantry's Website](http://gantry.org)):
    * [Logo](http://docs.gantry.org/gantry5/particles/logo)
    * [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    * [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    * [Social](http://docs.gantry.org/gantry5/particles/social)
    * [Widget Positions](http://docs.gantry.org/gantry5/particles/position)
    * [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    * [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    * [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    * [Widget Instance](http://docs.gantry.org/gantry5/particles/module-instance)
    * [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    * [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Sienna:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Sienna RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Sienna demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several widget and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Sienna demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpg)

In order to make it really easy to replicate the home page, we included a layout preset for the home page with the theme. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout. If you downloaded the theme and not a RocketLauncher, this is the best option for you if you want a copy of the front page with minimal effort.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpg)

Sienna has its own built-in Menu Editor which takes full advantage of WordPress's menu system, taking your WordPress menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way WordPress sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Sienna Theme > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Sienna Theme** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.

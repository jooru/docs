---
title: Kraken: Recreating the Demo
description: Your Guide to Recreating Elements of the Kraken Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/kraken:Kraken

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Kraken can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Kraken Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/kraken.jpeg)

:   1. **FixedSide** Logo (Particle) [1%, 3%, se]
    2. **FixedSide** Social (Particle) [4%, 3%, se]
    3. **FixedSide** Side Menu (Position) [5%, 3%, se]
    4. **Header** Swiper (Particle) [7%, 30%, se]
    5. **Header** Swiper (Particle) [15%, 20%, se]
    6. **Showcase** Grid Statistic (Particle) [25%, 20%, se]
    7. **Above** Grid Content (Particle) [33%, 20%, se]
    8. **Utility** Custom HTML (Particle) [45%, 20%, se]
    9. **Mainbar** Grid Content (Particle) [49%, 20%, se]
    10. **Aside** Icon Menu (Particle) [49%, 65%, se]
    11. **Aside** Grid Content (Particle) [54%, 65%, se]
    12. **Aside** Block Content (Particle) [64%, 65%, se]
    13. **Aside** Swiper (Particle) [74%, 65%, se]
    14. **Extension** Swiper (particle) [90%, 35%, se]
    15. **Footer** Logo (Particle) [97%, 15%, se]
    16. **Footer** Horizontal Menu (Particle) [97%, 40%, se]
    17. **Footer** Social (Particle) [97%, 77%, se]
    18. **Copyright** Branding (Particle) [99%, 15%, se]
    19. **Copyright** Copyright (Particle) [99%, 45%, se]
    20. **Copyright** To Top (Particle) [99%, 85%, se]

Particles
-----

Here is a list of particles that are available in Kraken, as well as links to documentation to help you get started:

>> All Home Particles can be edited via **Gantry 5 > Home > Layout**. Any additional particles that are found in the Subpages of our Kraken RocketLauncher can be located via its respective Outline.

* Theme Particles
    - [Block Content](particle_block.md)
    - [Chartist](particle_chartist.md)
    - [Contact](particle_contact.md)
    - [Content List](particle_contentlist.md)
    - [FlexSlider](particle_flexslider.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grav Content](particle_grav.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [News Ticker](particle_newsticker.md)
    - [Newsletter](particle_newsletter.md)
    - [News Slider](particle_newsslider.md)
    - [Overlay Toggle](particle_overlay.md)
    - [Promo Content](particle_promocontent.md)
    - [Pricing Table](particle_pricing.md)
    - [Promo Image](particle_promoimage.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Testimonial](particle_testimonial.md)
* Core Particles 
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Recommended Plugins
-----

Here is a list of RocketTheme plugins used to create the demo version of Kraken:

* [Gantry 5 Theme Framework](http://gantry.org/)

Many of these plugins are included with the Kraken RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Kraken demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Kraken demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Kraken has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.

---
title: Versla: Recreating the Demo
description: Your Guide to Recreating Elements of the Versla Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/versla:Versla

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Versla can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Versla Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particles as they appear on the front page of our demo. These can all be found and edited via Templates > Versla - Home > Layout.

![](assets/versla2.jpeg)

:   1. **Navigation** Logo (Particle) [1%, 13%, se]
    2. **Navigation** Menu (Particle) [1%, 27%, se]
    3. **Navigation** Shopping Cart (Particle) [1%, 75%, se]
    4. **Slideshow** Simple Content (Particle) [5%, 27%, se]
    5. **Slideshow** Owl Showcase (Particle) [8%, 3%, se]
    6. **Header** Product List (Particle) [20%, 10% se]
    7. **Above** Info List (Particle) [50%, 15%, se]
    8. **Feature** Owl Preview (Particle) [60%, 15%, se]
    9. **Expanded** Simple Content (Particle) [73%, 5%, se]
    10. **Expanded** Joomla Articles (Particle) [73%, 52%, se]
    11. **Footer** Simple Content (Particle) [90%, 12%, se]
    12. **Footer** Newsletter (Particle) [90%, 62%, se]
    13. **Copyright** Bottom Menu (Particle) [95%, 10%, se]
    14. **Copyright** Branding (Particle) [95%, 70%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Versla, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Templates > Versla - Home > Layout. Any additional particles that are found in the Subpages of our Versla RocketLauncher can be located via your Joomla Administrator > Extensions > Modules. Joomla allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

* Template Particles
    * [Owl Carousel](particle_owl.md)
    * [Shopping Cart](particle_shopping.md)
    * [Product List](particle_productlist.md)
    * [Video and Video Grid](particle_video.md)
    * [Content Tabs](particle_tabs.md)
    * [Pricing Table](particle_pricing.md)
    * [Joomla Articles](particle_joomla.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Simple Content](particle_simple.md)
    * [Simple Menu](particle_simplemenu.md)
    * [Image Grid](particle_image.md)
    * [Swiper](particle_swiper.md)

* Core Particles (Documented on [Gantry's Website](http://gantry.org)):
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

Here is a list of RocketTheme extensions used to create the demo version of Versla:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Versla RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Versla demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Versla demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

If you did not choose to 'Install Sample Data' upon installing the Versla theme, we have included a convenient layout preset that enables you to load the home page as seen in our demo. This preset is called **Home - Particles** and it includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access this preset by selecting **Load** in the **Layout Manager**.

>> Note: When loading the **Home - Particles** preset, our Content Array particle used in our demo will be replaced with a Custom HTML particle.

Menu Editor
-----

![](assets/menu_1.jpeg)

Versla has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Versla > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Versla** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.

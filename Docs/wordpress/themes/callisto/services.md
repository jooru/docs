---
title: Callisto: Recreating the Demo - Services Page
description: Your Guide to Recreating Elements of the Callisto Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/callisto:Callisto

---

## Introduction

The **Services** example page demonstrates how you can create a beautiful page with the Callisto theme. Here is some information to help you replicate this page as it appears in the demo.

>> Any **Custom HTML** particles are available and set in the **Layout Manager**, not as **Text** widgets.

## Layout Manager

![Layout Manager](assets/layout_services.jpeg)

This is a look at the **Layout Manager** for the **Callisto - Pages - Services** outline. We have detailed the various particles represented here in the sections below.

## Widgets and Particles

Below is a brief rundown of the widgets and particles used to make up the demo page.

![](assets/page_services.jpeg)

:   1. **Header - Logo** [6%, 11%, se]
    2. **Header - Icon Menu** [6%, 55%, se]
    3. **Navigation - Menu** [10%, 11%, se]
    4. **Navigation - Social** [10%, 78%, se]
    5. **Showcase - Custom HTML** [13%, 40%, se]
    6. **Mainbar - Custom HTML** [19%, 10%, se]
    7. **Mainbar - Custom HTML** [19%, 38%, se]
    8. **Mainbar - Custom HTML** [19%, 65%, se]
    9. **Mainbar - Custom HTML** [29%, 10%, se]
    10. **Mainbar - Custom HTML** [29%, 38%, se]
    11. **Mainbar - Custom HTML** [29%, 65%, se]
    12. **Mainbar - Content List** [40%, 11%, se]
    13. **Mainbar - Info List** [55%, 11%, se]
    14. **Mainbar - Info List** [55%, 38%, se]
    15. **Mainbar - Info List** [55%, 65%, se]
    16. **Extension - Custom HTML** [70%, 40%, se]
    17. **Footer - Custom HTML** [80%, 11%, se]
    18. **Footer - Newsletter** [80%, 38%, se]
    19. **Footer - Custom HTML - Copyright** [80%, 65%, se]
    20. **Copyright - Copyright** [92%, 40%, se]

1. [Header](#header-section)
2. [Navigation](#navigation-section)
3. [Showcase](#showcase-section)
4. [Mainbar](#mainbar-section)
5. [Extension](#plugin-section)
6. [Footer](#footer-section)
7. [Copyright](#copyright-section)

## Header Section

![](assets/page_aboutus_1.jpeg)

:   1. **Logo (Particle)** [40%, 5%, se]
    2. **Icon Menu (Particle)** [40%, 60%, se]

The **Header** section is made up of a position and two particles set in two rows. The first row hosts the **System Messages** position which remains invisible unless a system message is being displayed to the visitor.

In the second row, we have a **Logo** particle and an **Icon Menu** particle which make up the visual body of this area of the site. Settings used in our demo for each of these particles can be found below.

### Logo (Particle)

#### Particle Settings

| Field       | Setting    |
| :-----      | :-----     |
| Title       | `Logo`     |
| URL         | Blank      |
| Image       | Custom     |
| Text        | `Callisto` |
| CSS Classes | `g-logo`   |

#### Block Settings

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `g-logo-block` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `56%`          |

### Icon Menu (Particle)

#### Particle Settings

| Field                  | Setting          |
| :-----                 | :-----           |
| CSS Classes            | Blank            |
| Target                 | Self             |
| Icon Menu Item 1 Title | `Features`       |
| Icon Menu Item 1 Icon  | `fa fa-diamond`  |
| Icon Menu Item 1 Text  | `Features`       |
| Icon Menu Item 1 Link  | `#`              |
| Icon Menu Item 2 Title | `Gantry 5`       |
| Icon Menu Item 2 Icon  | `fa fa-rocket`   |
| Icon Menu Item 2 Text  | `Gantry 5`       |
| Icon Menu Item 2 Link  | `#`              |
| Icon Menu Item 3 Title | `Addons`         |
| Icon Menu Item 3 Icon  | `fa fa-gear`     |
| Icon Menu Item 3 Text  | `Addons`         |
| Icon Menu Item 3 Link  | `#`              |
| Icon Menu Item 4 Title | `Download`       |
| Icon Menu Item 4 Icon  | `fa fa-download` |
| Icon Menu Item 4 Text  | `Download`       |
| Icon Menu Item 4 Link  | `#`              |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | `flush` |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `44%`   |

## Navigation Section

![](assets/page_aboutus_2.jpeg)

:   1. **Menu (Particle)** [40%, 5%, se]
    2. **Social** [40%, 85%, se]

The **Navigation** section is made up of two particles. The first is a **Menu** particle which displays a CMS-sourced menu which can be enhanced through Gantry's **Menu Editor**. The second particle in the section is the **Social** particle, displaying social links.

Settings used in our demo for each of these particles can be found below.

### Menu (Particle)

#### Particle Settings

| Field       | Setting |
| :-----      | :-----  |
| Title       | `Menu`  |
| Base Path   | `/`     |
| Menu        | Custom  |
| Start Level | `1`     |
| Max Levels  | `0`     |

#### Block Settings

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `g-menu-block` |
| Variations     | Blank          |
| Tag Attributes | Blank          |
| Block Size     | `80%`          |

### Social (Particle)

#### Particle Settings

| Field               | Setting                                          |
| :-----              | :-----                                           |
| Title               | Social                                           |
| CSS Classes         | `social-items`                                   |
| Social Items        | `Features`                                       |
| Social Item 1 Title | `Twitter`                                        |
| Social Item 1 Icon  | `fa fa-twitter fa-fw`                            |
| Social Item 1 Text  | Blank                                            |
| Social Item 1 Link  | `http://twitter.com/rockettheme`                 |
| Social Item 2 Title | `Facebook`                                       |
| Social Item 2 Icon  | `fa fa-facebook fa-fw`                           |
| Social Item 2 Text  | Blank                                            |
| Social Item 2 Link  | `http://facebook.com/rockettheme`                |
| Social Item 3 Title | `Google`                                         |
| Social Item 3 Icon  | `fa fa-google fa-fw`                             |
| Social Item 3 Text  | Blank                                            |
| Social Item 3 Link  | `http://plus.google.com/+rockettheme`            |
| Social Item 4 Title | `RSS`                                            |
| Social Item 4 Icon  | `fa fa-rss fa-fw`                                |
| Social Item 4 Text  | Blank                                            |
| Social Item 4 Link  | `http://www.rockettheme.com/product-updates?rss` |

#### Block Settings

| Field          | Setting |
| :-----         | :-----  |
| CSS ID         | Blank   |
| CSS Classes    | Blank   |
| Variations     | Blank   |
| Tag Attributes | Blank   |
| Block Size     | `20%`   |

## Showcase Section

![](assets/page_services_1.jpeg)

The **Showcase** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field         | Setting      |
| :-----        | :-----       |
| Particle Name | `What We Do` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">What We Do</h2>
    <div class="g-layercontent-subtitle">Learn More About Our Great Services</div>
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | Blank           |
| Tag Attributes | Blank           |
| Block Size     | `100%`          |

## Mainbar Section

![](assets/page_services_2.jpeg)

:   1. **Custom HTML 1** [6%, 6%, se]
    2. **Custom HTML 2** [6%, 36%, se]
    3. **Custom HTML 3** [6%, 66%, se]
    4. **Custom HTML 4** [24%, 6%, se]
    5. **Custom HTML 5** [24%, 36%, se]
    6. **Custom HTML 6** [24%, 66%, se]
    7. **Content List** [42%, 6%, se]
    8. **Info List 1** [69%, 6%, se]
    9. **Info List 2** [69%, 36%, se]
    10. **Info List 3** [69%, 66%, se]

The **Mainbar** section itself renders as 100% of the page width as there are no particles or positions assigned to the Sidebar section. With this in mind, the **Mainbar** section is set to `67`% width and the **Sidebar** section to `33`%.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting   |
| :-----        | :-----    |
| Particle Name | `Desktop` |

**Custom HTML**
~~~ .html
<span class="fa fa-desktop fa-3x"></span>
<h2 class="g-title">Desktop Apps</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `Center`   |
| Variations     | `Box Blue` |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting  |
| :-----        | :-----   |
| Particle Name | `Mobile` |

**Custom HTML**
~~~ .html
<span class="fa fa-mobile fa-3x"></span>
<h2 class="g-title">Mobile Apps</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `center`   |
| Variations     | `Box Grey` |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 3 (Particle)

#### Particle Settings

| Field         | Setting |
| :-----        | :-----  |
| Particle Name | `Cloud` |

**Custom HTML**
~~~ .html
<span class="fa fa-cloud fa-3x"></span>
<h2 class="g-title">Cloud Servers</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting      |
| :-----         | :-----       |
| CSS ID         | Blank        |
| CSS Classes    | `center`     |
| Variations     | `Box Orange` |
| Tag Attributes | Blank        |
| Block Size     | `33.3333%`   |

### Custom HTML 4 (Particle)

#### Particle Settings

| Field         | Setting     |
| :-----        | :-----      |
| Particle Name | `Databases` |

**Custom HTML**
~~~ .html
<span class="fa fa-database fa-3x"></span>
<h2 class="g-title">Databases</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `center`   |
| Variations     | `Box Pink` |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Custom HTML 5 (Particle)

#### Particle Settings

| Field         | Setting    |
| :-----        | :-----     |
| Particle Name | `Graphics` |

**Custom HTML**
~~~ .html
<span class="fa fa-bar-chart-o fa-3x"></span>
<h2 class="g-title">Graphics</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting      |
| :-----         | :-----       |
| CSS ID         | Blank        |
| CSS Classes    | `center`     |
| Variations     | `Box Purple` |
| Tag Attributes | Blank        |
| Block Size     | `33.3333%`   |

### Custom HTML 6 (Particle)

#### Particle Settings

| Field         | Setting   |
| :-----        | :-----    |
| Particle Name | `Analyst` |

**Custom HTML**
~~~ .html
<span class="fa fa-calculator fa-3x"></span>
<h2 class="g-title">Analyst</h2>
<p>Collaboratively administrate empowered markets via available great networks.</p>
~~~

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | `center`   |
| Variations     | `Box Red`  |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Content List (Particle)

#### Particle Settings

| Field         | Setting                                        |
| :-----        | :-----                                         |
| Particle Name | `Why Choose Us`                                |
| CSS Classes   | Blank                                          |
| Image         | Custom                                         |
| Image Tag     | `Services`                                     |
| Headline      | `Why Choose Us`                                |
| Subtitle      | `Absolutely Stunning Design and Functionality` |
| Readmore Text | `Learn More`                                   |
| Readmore Link | `#`                                            |
| Grid Column   | 2 Columns                                      |
| Content Lists | Blank                                          |

**Description**
~~~ .html
Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions. Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI. Dynamically innovate resource-leveling customer service for state of the art customer service.
~~~

#### Block Settings

| Field          | Setting        |
| :-----         | :-----         |
| CSS ID         | Blank          |
| CSS Classes    | `nopaddingall` |
| Variations     | `Box 2`        |
| Tag Attributes | Blank          |
| Block Size     | `100%`         |

### Info List 1 (Particle)

#### Particle Settings

| Field                         | Setting                                                              |
| :-----                        | :-----                                                               |
| Particle Name                 | `Graphic Design`                                                     |
| CSS Classes                   | Blank                                                                |
| Title                         | Blank                                                                |
| Info Lists Item 1 Title       | `Graphic Design`                                                     |
| Info Lists Item 1 Link        | `#`                                                                  |
| Info Lists Item 1 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 2 Title       | `Domain`                                                             |
| Info Lists Item 2 Link        | `#`                                                                  |
| Info Lists Item 2 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 3 Title       | `HelpDesk`                                                           |
| Info Lists Item 3 Link        | `#`                                                                  |
| Info Lists Item 3 Description | `Dynamically procrastinate B2C users after installed base benefits.` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Info List 2 (Particle)

#### Particle Settings

| Field                         | Setting                                                              |
| :-----                        | :-----                                                               |
| Particle Name                 | `Programming`                                                     |
| CSS Classes                   | Blank                                                                |
| Title                         | Blank                                                                |
| Info Lists Item 1 Title       | `Programming`                                                     |
| Info Lists Item 1 Link        | `#`                                                                  |
| Info Lists Item 1 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 2 Title       | `Security`                                                             |
| Info Lists Item 2 Link        | `#`                                                                  |
| Info Lists Item 2 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 3 Title       | `Theme`                                                           |
| Info Lists Item 3 Link        | `#`                                                                  |
| Info Lists Item 3 Description | `Dynamically procrastinate B2C users after installed base benefits.` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

### Info List 3 (Particle)

#### Particle Settings

| Field                         | Setting                                                              |
| :-----                        | :-----                                                               |
| Particle Name                 | `Hosting`                                                     |
| CSS Classes                   | Blank                                                                |
| Title                         | Blank                                                                |
| Info Lists Item 1 Title       | `Hosting`                                                     |
| Info Lists Item 1 Link        | `#`                                                                  |
| Info Lists Item 1 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 2 Title       | `Server`                                                             |
| Info Lists Item 2 Link        | `#`                                                                  |
| Info Lists Item 2 Description | `Dynamically procrastinate B2C users after installed base benefits.` |
| Info Lists Item 3 Title       | `Marketplace`                                                           |
| Info Lists Item 3 Link        | `#`                                                                  |
| Info Lists Item 3 Description | `Dynamically procrastinate B2C users after installed base benefits.` |

#### Block Settings

| Field          | Setting    |
| :-----         | :-----     |
| CSS ID         | Blank      |
| CSS Classes    | Blank      |
| Variations     | `Box 3`    |
| Tag Attributes | Blank      |
| Block Size     | `33.3333%` |

## Extension Section

![](assets/page_ourteam_3.jpeg)

The **Extension** section contains a single **Custom HTML** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field       | Setting       |
| :-----      | :-----        |
| Particle Name       | `Save Time and Effort` |

**Custom HTML**
~~~ .html
<div class="g-layercontent g-layercontent-small">
    <h2 class="g-layercontent-title">Save Time and Effort</h2>
    <div class="g-layercontent-subtitle">We Always Create the Real Value and Work with All Passion</div>
    <a href="#" class="button button-2">Purchase Callisto</a>
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | `Box 1`         |
| Tag Attributes | Blank           |
| Block Size     | `100%`          |

## Footer Section

![](assets/page_aboutus_6.jpeg)

:   1. **Custom HTML 1** [30%, 5%, se]
    2. **Newsletter** [30%, 38%, se]
    3. **Custom HTML 2** [30%, 70%, se]

The **Footer** section is made up of three particles in a single row. This includes a **Newsletter** particle surrounded by two **Custom HTML** particles.

Settings used in our demo for each of these particles can be found below.

### Custom HTML 1 (Particle)

#### Particle Settings

| Field         | Setting          |
| :-----        | :-----           |
| Particle Name | `About Callisto` |

**Custom HTML**
~~~ .html
<h2 class="g-title">About Callisto</h2>

<p>All demo content is for sample purposes only, intended to represent a live site.</p>

<p>The sample pages are intended to show how Callisto can be constructed on your site.</p>
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | Blank            |
| Variations     | Blank            |
| Tag Attributes | Blank            |
| Block Size     | `33.3333333333%` |

### Newsletter (Particle)

#### Particle Settings

| Field          | Setting           |
| :-----         | :-----            |
| Particle Name  | `Newsletter`      |
| CSS Classes    | Blank             |
| Title          | `Newsletter`      |
| Feedburner URI | `rocketthemeblog` |

**Heading Text**
~~~ .html
Subscribe to our newsletter and stay updated on the latest developments and special offers!
~~~

#### Block Settings

| Field          | Setting          |
| :-----         | :-----           |
| CSS ID         | Blank            |
| CSS Classes    | `flush, center`  |
| Variations     | `Box 1`          |
| Tag Attributes | Blank            |
| Block Size     | `33.3333666666%` |

### Custom HTML 2 (Particle)

#### Particle Settings

| Field         | Setting          |
| :-----        | :-----           |
| Particle Name | `Simple Sitemap` |

**Custom HTML**
~~~ .html
<h2 class="g-title">Sample Sitemap</h2>

<div class="g-grid">
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="#">Home</a></li>
            <li><a href="#">Features</a></li>
            <li><a href="#">Typography</a></li>
            <li><a href="#">Particles</a></li>
            <li><a href="#">Variations</a></li>
        </ul>       
    </div>
    <div class="g-block">
        <ul class="nomarginall noliststyle">
            <li><a href="#">Buttons</a></li>
            <li><a href="#">Pages</a></li>
            <li><a href="#">Guide</a></li>
            <li><a href="#">Support</a></li>
            <li><a href="#">Download</a></li>
        </ul>       
    </div>  
</div>
~~~

#### Block Settings

| Field          | Setting         |
| :-----         | :-----          |
| CSS ID         | Blank           |
| CSS Classes    | `flush, center` |
| Variations     | `Box 1`         |
| Tag Attributes | Blank           |
| Block Size     | `33.3333%`      |

## Copyright Section

![](assets/page_aboutus_7.jpeg)

The **Copyright** section contains a single **Copyright** particle. Settings used in our demo for this particle can be found below.

### Custom HTML (Particle)

#### Particle Settings

| Field           | Setting            |
| :-----          | :-----             |
| Particle Name   | `Copyright`        |
| Start Year      | `2007`             |
| End Year        | Now                |
| Copyright Owner | `RocketTheme, LLC` |

#### Block Settings

| Field          | Setting  |
| :-----         | :-----   |
| CSS ID         | Blank    |
| CSS Classes    | `center` |
| Variations     | Blank    |
| Tag Attributes | Blank    |
| Block Size     | `100%`   |

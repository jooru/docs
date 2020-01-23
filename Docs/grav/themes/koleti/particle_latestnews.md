---
title: Koleti: Latest News Particle
description: Your Guide to Recreating Elements of the Koleti Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/koleti:Koleti

---

## Introduction

![](assets/particle_latestnews1.png)

The **Latest News** particle displays your latest posts or featured content, along with images and text.

Here are the topics covered in this guide:

* [Configuration](#configuration)
    - [Main Options](#settings)
    - [Item Options](#particle-item-options)
    - [Posts](#articles)
    - [Display](#display)

## Configuration

### Settings 

These options affect the main area of the particle, and not the individual items within. You can set the title of the particle, as well as give it an introductory paragraph here.

![](assets/particle_latestnews2.png)

| Option            | Description                                                                                         |
| :-----            | :-----                                                                                              |
| Particle Name     | This is the name of the particle used for back end management. It does not appear on the front end. |
| Content Source    | Choose between **Particle** and **Grav** as the Content Source.               |
| CSS Classes       | Enter any CSS class(es) you wish to have apply to the particle.                 |
| Margin Top Value  | Set the value for the margin-top for the particle's content. (example: `-7rem`) |
| Grid Column       | Set the number of columns items appear in.                                      |

### Particle Item Options

These items make up the individual featured items in the particle. Items in this section will only appear if **Particle** is selected as the **Content Source**.

![](assets/particle_latestnews3.png)

![](assets/particle_latestnews4.png)

| Option      | Description                                                                              |
| :-----      | :-----                                                                                   |
| Item Name   | This is the name of the item. This appears as the item's title on the front end.         |
| Layout      | Choose between **Photo**, **Quote**, and **Text** as the layout type for the item. |
| Image       | Set an image to appear in the item.                                                      |
| Description | Enter a text description for the item.                                                   |
| URL         | Enter a URL you would like the item to link to.                                          |
| Target      | Set a target window for the read more link.                                              |

### Posts

![](assets/particle_latestnews5.png)

| Option             | Description                                                                            |
| :-----             | :-----                                                                                 |
| Categories         | Enter the categories of posts this particle will display.                              |
| Number of Pages    | Enter the maximum number of pages to display.                                          |
| Start From         | Enter offset specifying the first post to return. The default is '0' (the first post). |
| Order By           | Choose the type of factor to order by.                                                 |
| Ordering Direction | Choose between **Ascending** and **Descending** as the post ordering method.           |

### Display

This section configures how posts are displayed.

![](assets/particle_latestnews6.png)

| Option          | Description                                                                                                             |
| :-----          | :-----                                                                                                                  |
| Image           | Choose to **Show** or **Hide** the post's image.                                                                        |
| Article Text    | Choose between **Introduction**, **Full Article**, and **Hide** to determine which content is displayed with each item. |
| Text Limit      | Set a limit (in characters) for the post text displayed.                                                                |
| Text Formatting | Choose between **HTML** and **Plain Text** formatting for the post's text.                                              |
| Category        | Choose to **Show** or **Hide** the post's category.                                                                     |
| Title           | **Show** or **Hide** the post's title.                                                                                  |
| Title Limit     | Enter the maximum number of characters in the title to display.                                                         |
| Link            | **Show** or **Hide** the Read More link.                                                                                |
| Target          | Set a target window for the read more link.                                                                             |

>> Note: When using Grav Content source, images can utilize the **Photo Large** layout by creating the Tag **photo-large** for the Page(s) you are displaying.

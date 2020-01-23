---
title: Kirigami: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Kirigami Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/kirigami:Kirigami

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Kirigami Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style
| Override |                 Option |                                    Setting |  
| :------- | ---------------------: | -----------------------------------------: |  
| Default  |                   Logo |                                   Kirigami |  
| Default  |    Featured Image Size |    Width: 525, Height: 303, Position: Left |  
| Default  |          Font Settings |  Font Family: Kirigami, Font Size: Default |  
| Default  |             Pagination | Enabled: On, Show Count: On, Side Pages: 8 |  
| Default  | Use WordPress Comments |                                         On |  
| Default  |             Custom CSS |                                      Blank |  

### Gizmos
| Override |                Option |                      Setting |  
| :------- | --------------------: | ---------------------------: |  
| Default  |           Page Suffix |   Enabled: Off, Class: Blank |  
| Default  |            Feed Links |                           On |  
| Default  |      Custom Title Tag |                        Blank |  
| Default  | Shortcodes in Widgets |                           On |  
| Default  |              RokStyle |                           On |  
| Default  |      Google Analytics | Enabled: Off, UA Code: Blank |  

### Layouts

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Header Positions     | Positions: 2, 3:9     |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainTop Positions    | Positions: 1, 12      |  
| Default | MainBody Positions   | Positions: 2, 9:3     |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 4, 3:3:3:3 |  
| Default | Bottom Positions     | Positions: 4, 3:3:3:3 |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 3, 4:6:2   |  

### Advanced
| Override |                  Option |                                Setting |  
| :------- | ----------------------: | -------------------------------------: |  
| Default  |             Layout Mode |                             Responsive |  
| Default  |        Maintenance Mode |                                    Off |  
| Default  |         Display Content |                                     On |  
| Default  |        Display Mainbody |                                     On |  
| Default  |             RTL Support |                                     On |  
| Default  |          RTL Typography | Enabled: On, Typography Styling: Light |  
| Default  | Disable Auto Paragraphs |        Enabled: On, Content Type: Both |  
| Default  |       Disable Texturize |                                    Off |  
| Default  |             Selectivizr |                                    Off |  

### Assignments
| Override   |              Option |               Setting |  
| :--------- | ------------------: | --------------------: |  
| Front Page | Theme Page Types | Home Page, Front Page |  

[override]: http://docs.gantry.org/gantry4/configure
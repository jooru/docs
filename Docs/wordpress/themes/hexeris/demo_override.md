---
title: Hexeris: Recreating the Demo - Overrides
description: Your Guide to Recreating Elements of the Hexeris Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hexeris:Hexeris

---

Theme Override Settings
-----

One of the most important central features of any Gantry theme is the ability to be set up within the Theme Settings menu. These settings can be adjusted by navigating to **Administration -> Hexeris Theme**. To replicate the demo, the main changes being made will happen within the Style, Gizmos, Layouts, and Advanced tabs. 

![][demo]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a theme preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Theme Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo. Keep in mind that the override indicated here relates to the theme override in this menu. More information about how overrides work can be found in our [Gantry documentation][override].

### Style

| Override |                 Option |                                    Setting |  
| :------- | ---------------------: | -----------------------------------------: |  
| Default  |                   Logo |                           Hexeris theme |  
| Default  |        Responsive Menu |                                      Panel |  
| Default  |    Featured Image Size |    Width: 380, Height: 220, Position: Left |  
| Default  |          Font Settings |   Font Family: Hexeris, Font Size: Default |  
| Default  |             Pagination | Enabled: On, Show Count: On, Side Pages: 8 |  
| Default  | Use WordPress Comments |                                         On |  
| Default  |             Custom CSS |                                      Blank |   

### Gizmos

| Override   |                Option |                          Setting |  
| :--------- | --------------------: | -------------------------------: |   
| Default    |           Page Suffix |       Enabled: Off, Class: Blank |  
| Default    |            Feed Links |                               On |  
| Default    |      Custom Title Tag |                            Blank |  
| Default    | Shortcodes in Widgets |                               On |  
| Default    |              RokStyle |                               On |  
| Default    |      Google Analytics |     Enabled: Off, UA Code: Blank |  

### Layouts

| Style   | Option               | Setting               |  
| :------ | :------------------- | :-------------------- |  
| Default | Top Positions        | Positions: 4, 3:3:3:3 |  
| Default | Header Positions     | Positions: 3, 3:7:2   |  
| Default | Showcase Positions   | Positions: 1, 12      |  
| Default | Feature Positions    | Positions: 1, 12      |  
| Default | Utility Positions    | Positions: 1, 12      |  
| Default | MainTop Positions    | Positions: 4, 3:3:3:3 |  
| Default | MainBody Positions   | Positions: 1, 12      |  
| Default | MainBottom Positions | Positions: 4, 3:3:3:3 |  
| Default | Extension Positions  | Positions: 3, 4:4:4   |  
| Default | Bottom Positions     | Positions: 1, 12      |  
| Default | Footer Positions     | Positions: 3, 4:4:4   |  
| Default | Copyright Positions  | Positions: 2, 6:6     |  

### Advanced

| Override   |                  Option |                                     Setting |  
| :--------- | ----------------------: | ------------------------------------------: |  
| Default    |             Layout Mode |                                  Responsive |  
| Default    |        Maintenance Mode |                                         Off |  
| Default    |         Load Transition |                                         Off |  
| Default    |         Display Content |                                          On |  
| Default    |        Display Mainbody |                                          On |  
| Default    |             RTL Support |                                          On |  
| Default    | Disable Auto Paragraphs |             Enabled: On, Content Type: Both |  
| Default    |       Disable Texturize |                                         Off |  
| Default    |             Selectivizr |                                         Off |  
| Default    |           Less Compiler | CSS Compression: On, Compile: 2, Debug: Off |  
| Default    |            IE7 Redirect |                                          On |  
| Front Page |         Display Content |                                         Off |  

### Assignments

| Override   |              Option |               Setting |  
| :--------- | ------------------: | --------------------: |  
| Front Page | Theme Page Types | Home Page, Front Page |  

[demo]: assets/hexeris2.jpeg
[menu]: ../../start/menu.md
[override]: http://docs.gantry.org/gantry4/configure
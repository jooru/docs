---
title: Audacity: Audio Player Particle
description: Your Guide to Recreating Elements of the Audacity Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/audacity:Audacity

---

## Introduction

The **Audio Player** particle enables you to quickly and easily add embedded audio content to your page.

Here are the topics covered in this guide:

* [Configuration](#configuration)
  * [Main Options](#main-options)
  * [Item Options](#item-options)

## Configuration

### Main Options

These options affect the main area of the particle, and not the individual items within.

![Particle](assets/particle_audio2.png)

| Option               | Description                                                                                 |
| :-----               | :-----                                                                                      |
| Particle Name        | Enter the name you would like to assign to the particle. This only appears in the back end. |
| CSS Classes          | Sets any CSS class(es) you want to have apply to the particle's content.                    |
| Title                | Enter a title for the particle.                                                             |
| Now Playing Label    | Enter a label for the **Now Playing** section of the player.                                |
| Playlist Layout      | Choose whether or not you wish to have a scrollbar appear in the playlist.                  |
| Overflow Height      | Sets the overflow size (in pixels) for the playlist with the scrollbar.                    |


### Item Options

These items make up the individual featured items in the particle.

![Particle](assets/particle_audio3.png)

| Option            | Description                                                                                                       |
| :-----            | :-----                                                                                                            |
| Item Name         | Designates a name for the item that appears in the back end only.                                                 |
| Artist            | Enter an artist name that will be displayed with the item.                                                        |
| Track Title       | Enter a title for the track.                                                                                      |
| Album Cover       | Add cover art for the album that will be displayed along with the track in the particle.                          |
| Audio Source      | Enables you to select an external URL, or local audio file as the audio for the track.           |
| External URL      | If **External URL** is selected as the **Audio Source**, this is where you enter that URL.                        |
| Local Audio       | If **Local Audio** is selected as the **Audio Source**, this is where you enter the file's location or select it. |

The particle has local support for any audio format that can be natively embedded using HTML5. This includes: mp3, ogg, and wav.

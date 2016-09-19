---
title: Installing Omeka Everywhere Collections Viewer Software
---

This documentation is intended as a guide for those who want to deploy Omeka Everywhere in their institution or exhibit space(s). 

Omeka Everywhere Collection Viewer enables an institution to connect their Omeka Classic instance to an Ideum table or tablet with the Omeka Everywhere Connector installed along with the Open Exhibits software. Omeka Everywhere Collection Viewer uses the API of the Omeka Classic installation to pull particular collections or tags to populate an interactive experience for your visitors, without having to recreate any metadata.

## Key terms
- API: A way to make content on a website 
- Multi-touch device: a device which allows touch-screen interaction at more than one point. For the purposes of this documentation, an Ideum multitouch table or a tablet running Windows 7,8 or 10.
- Omeka Everywhere Connection Viewer: The connection between your Source and Target.
- Repository: the Omeka Classic installation from which you are drawing content for the interactive experience.
- Target: the tablet, touch table, or other touch screen on which your visitors will have an interactive experience. 
- Stage: The part of the visitor-facing table where items from the drawer are placed to be examined and interacted with.

## Preparing your Repository: Omeka Classic Installation
Omeka Everywhere pulls items from your repository using your collections and tags. As such, you will want to be certain that the items you intend to serve on the table or tablet are organized into collections and robustly tagged. 

You will also need to ensure that the API is enabled on your repository. (http://omeka.org/codex/Managing_API_Settings) 

### Tagging
Ensure that your tags are systematically applied (that you do not have both “cat” and “cats,” for example). 

You might want to create a list of key tags, as a controlled vocabulary, which users creating content can consult when tagging items. This will help ensure systematic application and consistency. 

### Best Practices: Item Files
Supported file types:
- Image: png, jpg, gif
- Video: mpeg–4, mp4, m4v, 3gpp, mov, flv, f4v
- Audio: mp3

File sizes: 

Shape: thumbnails in the browser load within a square space. Thin, tall, long images may not display well as thumbnails.
### Best practices: Item Content
Length: text display scales with the size of the media view, so making an item bigger doesn’t necessarily make more room for text. Keeping your descriptions short - roughly 100 words - will ensure a better display.

## Table Configuration
Please refer to the documentation from Ideum for the configuration and installation of the Omeka Everywhere Collection Viewer on your multi-touch device. [[link]]

## OECV Setup
Upon launching the Omeka Collection Viewer software, a menu will load giving you the options for repositories and themes. Select one repository and one theme from the dropdown menus and then click Accept.

It may take a few moments for the table to load content and theme.

An administrator can access this menu at any time by hitting 

Enter on an attached keyboard. 

## Visitor Experience
Once the Omeka Collection Viewer has launched, visitors can follow the prompts on the screen.

The interface loads a drawer at the bottom of the target or, if on a table, on the two long edges of the table. These can be opened or closed by the user.
[insert image]

When open, users can browse collections/tags through an alphabetical list. Note that the list is on continuous scroll - to get from Q to A one can scroll in either direction.
Once a user has selected a collection/tag, items from that collection or which use that tag will load in the drawer. Users can double-click on the an item to move it from the drawer to the stage.

A user interacting with an item on the stage can use pinch gestures to resize the item, use two fingers to rotate, and swipe to send the item across the table to a friend. Tapping on the i icon “flips” the item, displaying basic metadata.

To close an active item on the stage, 

Items on the stage will fade out and remove themselves from the stage after a set period of time (this is the attractTime setting in the configuration files)
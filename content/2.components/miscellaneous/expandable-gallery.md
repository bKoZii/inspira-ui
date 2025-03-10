---
title: Expandable Gallery
description: A responsive image gallery with an interactive hover effect that expands images dynamically.
navBadges:
  - value: New
    type: lime
---

::ComponentLoader{label="Preview" componentName="ExpandableGalleryDemo" type="examples" id="expandable-gallery"}
::

## API

| Prop Name | Type       | Default | Description                                    |
| --------- | ---------- | ------- | ---------------------------------------------- |
| `images`  | `string[]` | `[]`    | Array of image URLs to display in the gallery. |

## Component Code

You can copy and paste the following code to create this component:

::CodeViewer{filename="ExpandableGallery.vue" language="vue" componentName="ExpandableGallery" type="ui" id="expandable-gallery"}
::

## Features

- **Interactive Hover Effect**: Images expand when hovered over, creating a dynamic and engaging user experience.
- **Responsive Design**: The gallery automatically adjusts to the container size, ensuring it looks great on all devices.
- **Smooth Transitions**: Includes smooth scaling animations for a polished visual effect.
- **Customizable Content**: Easily update the `images` array to change the gallery's content.

## Credits

- Inspired from [Expandable Gallery Component by David Mráz](https://x.com/davidm_ml/status/1872319793124282653)

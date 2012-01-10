scaletopixelcount
=================

A Drupal image styles module to scale images to a maximum pixel count.

## INTRODUCTION

Sometimes galleries require thumbnails to be in their original aspect ratio.  This makes some galleries look untidy, and this is where scaling the thumbnail to a pixel count can help.

Inspired by the excellent Imagemagick, this module extends Drupal 7's core image styles feature to include an option to scale an image by pixel count - the image width * image height. This allows images to be scale according to the space they consume, rather than their dimensions along a single axis.  Additional options, however, are included to specify maximum width and height.

## INSTALLATION

* Clone the repository into /sites/all/modules/
* Visit /admin/modules to enable the module

## USAGE

* Go to /admin/config/media/image-styles/list and edit a style
* Add a Scale to pixel count effect
* Enter a Max pixel count (hint: square a preferred image width, ie. 240 * 240, to get your pixel count)


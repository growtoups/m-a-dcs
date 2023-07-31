Image Processing
=====

.. _convert:

Image Format Conversion
------------

## Overview

The Image Format Conversion route allows you to convert image files between various formats easily.

## Supported Formats

You can convert images from and to the following formats:

**Input Formats:** PNG, JPEG/JPG, WebP, TIFF

**Output Formats:** PNG, JPEG/JPG, WebP, TIFF

## How to Use

To convert an image, send a POST request to:

```
POST /api/images/convert
```

Include the input URL and desired output format in the request body as JSON:

{ "inputUrl": "https://example.com/input-image.png", "outputFormat": "webp" }

Replace `"https://example.com/input-image.png"` with your image URL and `"webp"` with the desired format.

## Privacy & Security

For enhanced privacy and security, all uploaded images are automatically deleted after 30 minutes.

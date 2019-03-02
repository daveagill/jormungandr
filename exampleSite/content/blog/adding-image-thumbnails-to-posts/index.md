+++
date = "2019-02-28"
title = "Adding Image Thumbnails To Posts"
author = "David Gill"
+++

Images that are bundled with pages can be added using the thumbnail shortcode. This shortcode adds them at a reduced resolution with a link to the full-size image.
This not only allows image-heavy pages to load faster but it also gives you control over how images are sized on your pages.

Here is an image thumbnail set to 200px height:

{{< thumbnail x200 "green-mamba.jpg" >}}

Here is an image thumbnail set to 400px width:

{{< thumbnail 400x "green-mamba.jpg" >}}
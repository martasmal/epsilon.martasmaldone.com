---
layout: page
subheadline:  "photo project"
title:  "Belgian journal"
teaser: " <a href='http://foundation.zurb.com/docs/components/clearing.html'>Clearing Lightbox</a>."
categories:
    - works
tags:
    - post format
header: no
image:
   thumb: "01.jpg"
gallery:
    - image_url: BEJ_anderlecht_2007.jpg
        # caption: generated caption for bistrot_2005.jpg 
    - image_url: BEJ_bistrot_liege2005.jpg
   # caption: generated caption for bistrot_liege2005.jpg 
    - image_url: BEJ_brussels_2005.jpg
   # caption: generated caption for brussels_2005.jpg 
    - image_url: BEJ_brussels_2007.jpg
   # caption: generated caption for brussels_2007.jpg 
    - image_url: BEJ_brussels_2011.jpg
   # caption: generated caption for brussels_2011.jpg 
    - image_url: BEJ_brussels_2012.jpg
   # caption: generated caption for brussels_2012.jpg 
    - image_url: BEJ_bxl_2006.jpg
   # caption: generated caption for bxl_2006.jpg 
    - image_url: BEJ_cattelan_2009.jpg
   # caption: generated caption for cattelan_2009.jpg 
    - image_url: BEJ_knokke_2009.jpg
   # caption: generated caption for knokke_2009.jpg 
    - image_url: BEJ_lagio_2006.jpg
   # caption: generated caption for lagio_2006.jpg 
    - image_url: BEJ_lamonnaie_2012.jpg
   # caption: generated caption for lamonnaie_2012.jpg 
    - image_url: BEJ_latifa_2006.jpg
   # caption: generated caption for latifa_2006.jpg 
    - image_url: BEJ_liege.jpg
   # caption: generated caption for liege.jpg 
    - image_url: BEJ_liege_2008.jpg
   # caption: generated caption for liege_2008.jpg 
    - image_url: BEJ_lustin_2009.jpg
   # caption: generated caption for lustin_2009.jpg 
    - image_url: BEJ_marcinelle_2010.jpg
   # caption: generated caption for marcinelle_2010.jpg 
    - image_url: BEJ_mingjia_2007.jpg
   # caption: generated caption for mingjia_2007.jpg 
    - image_url: BEJ_nationalday_2010.jpg
   # caption: generated caption for nationalday_2010.jpg 
    - image_url: BEJ_near_airport.jpg
   # caption: generated caption for near_airport.jpg 
    - image_url: BEJ_near_midi.jpg
   # caption: generated caption for near_midi.jpg 
    - image_url: BEJ_occupationbxl_2009.jpg
   # caption: generated caption for occupationbxl_2009.jpg 
    - image_url: BEJ_petitrien_2007.jpg
   # caption: generated caption for petitrien_2007.jpg 
    - image_url: BEJ_placestcatherine_2004.jpg
   # caption: generated caption for placestcatherine_2004.jpg 
    - image_url: BEJ_pocofa_2009.jpg
   # caption: generated caption for pocofa_2009.jpg 
    - image_url: BEJ_portedehal_2007.jpg
   # caption: generated caption for portedehal_2007.jpg 
    - image_url: BEJ_recyclart_2006.jpg
   # caption: generated caption for recyclart_2006.jpg 
    - image_url: BEJ_reddistrict_2010.jpg
   # caption: generated caption for reddistrict_2010.jpg 
    - image_url: BEJ_saintgilles_2006.jpg
   # caption: generated caption for saintgilles_2006.jpg 
    - image_url: BEJ_saintjosse_2012.jpg
   # caption: generated caption for saintjosse_2012.jpg 
    - image_url: BEJ_schaerbeek_2012.jpg
   # caption: generated caption for schaerbeek_2012.jpg 
    - image_url: BEJ_turkishbubblegum_2007.jpg
   # caption: generated caption for turkishbubblegum_2007.jpg 
    - image_url: BEJ_vilvoorde_2007.jpg
   # caption: generated caption for vilvoorde_2007.jpg 
    - image_url: BEJ_vottem_2005.jpg
   # caption: generated caption for vottem_2005.jpg 

---
You just need to choose a template like the [`page`][3]- or [`page-fullwidth`][4]-template and then just use `{% raw %}{% include gallery %}{% endraw %}`.
<!--more-->

{% include gallery %}


## How to embed a gallery

`{% raw %}{% include gallery %}{% endraw %}` lets you easily embed a gallery into your post. To use the gallery-include...


### Step 1

1. Make two images: a thumbnail and a big image.
2. Name the thumbnail *gallery-image-thumb.jpg* and...
3. ...name the big *gallery-image.jpg*.
4. Place them in the *images*-folder.


### Step 2

Define the big version in frontmatter,  

~~~
gallery:
    - image_url: gallery-image.jpg
~~~

If you like captions, give each image a caption:

~~~
gallery:
    - image_url: gallery-image.jpg
       caption: Starting Page with huge One Logo
~~~

### Step 3

Add the include whereever you want in your content with `{% raw %}{% include gallery %}{% endraw %}`.

{% include alert info='Have a look at this example-entry. And have a look into the images-folder. :)' %}











## Other Post Formats
{: .t60 }
{% include list-posts tag='post format' %}



 [1]: http://foundation.zurb.com/docs/components/clearing.html
 [2]: http://foundation.zurb.com/docs/components/block_grid.html
 [3]: {{ site.url }}{{ site.baseurl }}/design/page/
 [4]: {{ site.url }}{{ site.baseurl }}/design/page-fullwidth/

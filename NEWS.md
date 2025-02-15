## ggimage 0.2.2

+ `geom_bgimage` (2019-08-05, Mon)

## ggimage 0.2.1

+ `phylopic` now check the id by `phylopic_valid_id` (2019-01-16, Wed)
+ `phylopic_valid_id` check whether a silhouette image is exist
  - if not exist, then use `supertaxa`
  - if supertaxa is also not exist, use `subtaxa`
  - if subtaxa is also not exist, use `other` related taxa
  - otherwise, return NA
+ `phylopic_uid` supports querying phylopic uid from scientific name
+ three optional image color legend key (2018-12-11, Tue)
  - <https://github.com/GuangchuangYu/ggimage/issues/18>

## ggimage 0.2.0

+ `draw_key_image` that draws key of image colors using `rectGrob` (2018-12-10, Mon)
+ support `aes(color)` 
+ compatible with ggplot2 v3.1.0

## ggimage 0.1.8

+ support `pdf` file (2018-12-03, Mon)
+ support `svg` file
  - <https://github.com/GuangchuangYu/ggimage/issues/11>
+ `geom_twitchemote` layer

## ggimage 0.1.7

+ `geom_worldcup2018` layer (2018-06-19, Tue)

## ggimage 0.1.6

+ update url of `icon`and `list.icon` (2018-05-23, Wed)
+ mv `get_aes_var` to `rvcheck`

## ggimage 0.1.5

+ compatible with ggplot2-dev, v=2.2.1.9000 (2018-05-02, Wed)
+ `image_read2` internally use `magick::image_read` with additional feature to
  remove marginal empty space (2018-04-25, Wed)
+ re-export `ggplotify::as.grob` and `ggplotify::as.ggplot` (2018-04-24, Tue)

## ggimage 0.1.4

+ `ggbackground` for setting background image of ggplot (2018-04-18, Wed)

## ggimage 0.1.3

+ `geom_image` now accepts `asp` parameter to adjust aspect ratio of images
  (2018-03-22, Thu)

## ggimage 0.1.2

+ mv code in `toGrob` for base plot to `base2grob` pkg

## ggimage 0.1.1

+ add angle parameter <2017-12-27, Wed>

CHANGES IN VERSION 0.1.0
------------------------
 o update vignette <2017-12-04, Mon>
 o geom_subview now supports aes mapping <2017-11-21, Tue>

CHANGES IN VERSION 0.0.7
------------------------
 o geom_subview compatible with meme object <2017-10-24, Tue>
   + https://github.com/GuangchuangYu/meme

CHANGES IN VERSION 0.0.6
------------------------
 o add image_fun parameter; user can use magick function to process image <2017-10-17, Tue>
 o using magick to read image instead of EBImage <2017-10-17, Tue>

CHANGES IN VERSION 0.0.5
------------------------
 o geom_icon <2017-09-05, Wed>

CHANGES IN VERSION 0.0.4
------------------------
 o geom_emoji <2017-03-23, Thu>
 o geom_flag <2017-03-22, Wed>
 o support size = Inf <2017-03-22, Wed>
 o geom_phylopic layer <2017-03-22, Wed>
 o color parameter for geom_image and related layers <2017-03-22, Wed>
 o geom_pokemon <2017-03-22, Wed>

CHANGES IN VERSION 0.0.3
------------------------
 o geom_subview <2017-03-21, Tue>
 o theme_transparent from ggtree <2017-03-21, Tue>

CHANGES IN VERSION 0.0.2
------------------------
 o remove parsing `image` parameter via `...`, and set image="https://www.r-project.org/logo/Rlogo.png" by default <2017-02-22, Wed>

CHANGES IN VERSION 0.0.1
------------------------
 o geom_image layer <2017-02-21, Tue>

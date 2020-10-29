# cdn

> Static assets such as images and record for use with projects and other places on internet... are saved in `CDN server` for acceleration

> Pleas check `README` under each `/build/{sub_folder}` if you want to contribute.


## Developing and making pull requests

The [build](/build) directory gets deployed and is made available at the root of the top-level domain, that means the pull-zone in the CDN server should be made to the `build` directory:

- `https://chzionland.githublio/build/ => https://cdn.qizhong.land/`

And then you can fetch content such as [`/build/bg/bg1.webp`](/build/bg/bg1.webp) from CDN <https://cdn.qizhong.land/bg/bg1.webp>

You should already have pre-compiled, compressed and minified assets as needed as README.md in each folder, such as <https://github.com/chzionland/cdn/build/img/avtar/README.md>.


## Test CDN If Is Working

<https://cdn.qizhong.land/index.html>


## Reporting bugs and feature requests

You can report bugs and request features on [This Repository](https://github.com/chzionland/cdn/issues).

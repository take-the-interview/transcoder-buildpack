Heroku buildpack: FFMpeg + FFMpegthumbnailer
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [ffmpeg](http://www.ffmpeg.org/) and [ffmpegthumbnailer](https://code.google.com/p/ffmpegthumbnailer).
Use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine it with a real buildpack.

Usage
-----

```
    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-python.git
    https://github.com/take-the-interview/tti-transcoder-buildpack.git

    $ heroku create --buildpack https://github.com/ddollar/heroku-buildpack-multi.git

    $ git push heroku master
```

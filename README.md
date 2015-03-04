# &lt;hello-world&gt;

> Set a video as your HTML background.

## Demo

[Check it live!](http://hemanth.github.io/video-bg)

## Install

```sh
$ bower install video-bg --save
```

Or [download as ZIP](https://github.com/hemanth/video-bg/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/video-bg/dist/video-bg.html">
    ```

3. Start using it!

    ```html
    <video-bg srcs=["video.mp4","video.ogg", "video.webm"] muted="muted"></video-bg>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`srcs`     | *array*                   | ``                  | Array of fallback video URLs.
`muted`    | *string*                  | ``                  | "muted" or ""


## TODO

* Support few other attributes.

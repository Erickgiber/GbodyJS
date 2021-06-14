# ❤️ Gbody JS

This little library in development is for people who are just starting out in JavaScript programming.

## 🔥 How to start?

### You can start by adding this script to your HTML.
### <script src="https://n9.cl/gbodyjs"></script>
#### Or, you can download it directly from this repository.

**Always** put it first before the other scripts you have added!

### Video here!
[![Watch Video](https://i.ibb.co/gDWkQbp/js.png)](https://youtu.be/5MtmHlbt0Fw)

## 🔥 Selectors in Gbody JS.

### - Selector for everything! classes, id, attributes or HTML tags.
#### Some examples are:
```sh
s_('h1');

s_('.h1');

s_('#h1');

s_('[attribute="h1']);

let title = s_('h1');
title.textContent = "Hello, World!";


s_All('h1')[0];

let title_All = s_All('h1')[0];
title_All.textContent = "Hello, World!"
```

## 🔥 Dynamic audio with Gbody JS.

### - You can create audio element.
#### Some examples are:
```sh
audio_({
  src: "./src/media/audio.mp3",
  container: "body",
  controls: true,
  preload: true,
  autoplay: true
});
```

## 🔥 Dynamic image with Gbody JS.

### - You can create image element.
#### Some examples are:
```sh
image_({
  src: "./src/media/image.png",
  container: ".gallery"
});
```

## 🔥 Dynamic video with Gbody JS.

### - You can create video element.
#### Some examples are:
```sh
video_({
  src: "./src/media/video.mp4",
  container: ".content"
});
```

## ✅ Repeat Image with Gbody JS.

### - You can repeat image, video and audio element.
#### Some examples are:
```sh
const images = [
	"./src/media/1.mp3", // <-- Counter starting from here
	"./src/media/2.mp3",
	"./src/media/3.mp3",
	"./src/media/4.mp3"
];

image_({
  src: "./src/media/image.png",
  container: ".content",
  repeat: true,
  total: 4,
  counter: 0
});

// ⭐ For videos and audios it is the same procedure!
```

## ✅ Background sound.
### You can put a background audio with the following example:
```sh
bgSound_({
    src: "./src/media/myaudio.mp3"
});
// that easy
```

## ✅  Preloader
### You can put a background audio with the following example:
```sh
bgPreloader_({
    src: "<h1> Loading... </h1>",
    timeOut: 200 // <-- Seconds on ms
});
// that easy too
```

```sh
bgPreloader_({
    data: "img",
    src: "./src/media/preloader.gif", // or .png/.jpg
    timeOut: 200 // <-- Seconds on ms
});
// data: "img" or "video".
// if the data is not set, it will read the scr as pure html.
```

## ❤️ Change variable values ​​in CSS from JavaScript.
### You can change these values ​​like this:

## CSS Example:
```sh
:root {
    --bg: #fff;
    --color: #000;
}
```
## JS Example:
```sh
root_.setProperty('--bg', '#000');
------
// root_setProperty(name:variable, new:value);
```

### ❤️ Made with love by Giiber Developer!

# ❤️ Gbody JS

This little library in development is for people who are just starting out in JavaScript programming.

## 🔥 How to start?

### You can start by adding this script to your HTML.
### <script src="https://n9.cl/gbodyjs"></script>
#### Or, you can download it directly from this repository.

**Always** put it first before the other scripts you have added!

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

### Writing...

### ⭐ Made with love by Giiber Developer!

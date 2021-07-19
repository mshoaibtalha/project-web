### HTML Media

Multimedia is sound, music, videos, movies, and animations on web or on websites .Things which we can hear and see come to multimedia category.

#### Multimedia Format

Multimedia elements (like audio or video) are stored in media files.

The most common way to discover the type of a file, is to look at the file extension.

Multimedia files have formats and different extensions like: .wav, .mp3, .mp4, .mpg, .wmv, and .avi.

There are many audio and video format which are supported in HTML.

#### The HTML <video> Element

To show a video in HTML, use the `<video>` element:

```html
<video width="300" height="200">
  <source src="/html/vedio-audio/indila.mp4" type="video/mp4" />
</video>
```

##### Video Attributes

- control
- autoplay
- muted

#### The HTML `<audio>` Element

```html
<audio controls>
  <source src="/html/vedio-audio/indila.mp3" type="audio/mpeg" />
</audio>
```

##### Video Attributes

- control
- autoplay
- muted

## The HTML `<object>` Element

The `<object>` element is supported by all browsers.

The `<object>` element defines an embedded object within an HTML document.

It was designed to embed plug-ins (like Java applets, PDF readers, and Flash Players) in web pages, but can also be used to include HTML in HTML

```html
<object data="/html/element-attributes/element-attributes.html"></object>
```

#### The HTML `<object>` Element

The `<embed>` element is supported in all major browsers.

The `<embed>` element also defines an embedded object within an HTML document.

Web browsers have supported the <embed> element for a long time. However, it has not been a part of the HTML specification before HTML5.

```html
<embed src="/html/images/house.jpg" width="500" height="300" />
```

#### Playing a YouTube Video in HTML

To play your video on a web page, do the following:

- Upload the video to YouTube
- Take a note of the video id
- Define an `<iframe>` element in your web page
- Let the `src` attribute point to the video URL
- Use the `width` and `height` attributes to specify the dimension of the player
- Add any other parameters to the URL (see below)

```html
<iframe
  width="420"
  height="315"
  src="https://www.youtube.com/watch?v=mWRsgZuwf_8&ab_channel=ImagineDragonsVEVO"
>
</iframe>
```

source:www.w3school.com

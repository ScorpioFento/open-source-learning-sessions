# Lesson 3 — HTML Images, Links & Media  

**Path 1: HTML**  

Web pages are not limited to text. Images, links, and other media elements bring content to life. This lesson covers how to add images, create links, and embed multimedia such as audio and video.  

---

## Overview  

Images visually enhance web pages. Links connect documents and resources together. Multimedia elements like audio and video offer rich content experiences directly in the browser without additional plugins.  

---

## 🖼️ Images  

Images are added using the `<img>` element. The `src` attribute specifies the image source, and the `alt` attribute provides alternative text for accessibility and SEO.  

---

## 🔗 Links  

Links are created with the `<a>` element. The `href` attribute defines the destination URL. Additional attributes such as `target` and `rel` control how links behave.  

---

## 🎵 🎬 Multimedia  

HTML5 introduced `<audio>` and `<video>` elements to embed media files directly. They support attributes such as `controls` to provide play, pause, and volume options.  

---

## Code Example  

### Images  

```html
<img src="images/photo.jpg" alt="A beautiful landscape" width="600" height="400" />

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener">
  Learn more about HTML on MDN
</a>

<audio controls>
  <source src="audio/sample.mp3" type="audio/mpeg" />
  Your browser does not support the audio element.
</audio>

<video width="640" height="360" controls>
  <source src="video/sample.mp4" type="video/mp4" />
  Your browser does not support the video element.
</video>
```

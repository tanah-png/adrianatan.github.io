# Adriana Tan — Photography & Film Portfolio

A responsive, single-page portfolio site for photography and video work. It is built with plain HTML, CSS, and JavaScript, so it can be hosted directly with GitHub Pages.

## Preview / publish

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub Pages will publish the site and show its URL in the Pages settings.

## Personalize the site

- Replace the sample Unsplash image URLs in `index.html` with your own photography. Update the image alt text, captions, and location labels too.
- Update the short bio, page title, and email address (`hello@adrianatan.com`) with the details you want to share.
- Add video samples in the `videoSamples` list near the end of `index.html`. Each item takes a title, a public video URL, and a poster image URL, for example:

```js
{ title: 'A short film', url: 'https://vimeo.com/your-video-id', poster: 'https://your-image.jpg' }
```

The video section displays a helpful note until you add at least one sample. Video links open in a new tab.

The Google Fonts and Unsplash images used in the starter design are served by their respective providers and require an internet connection.

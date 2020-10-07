# Cube Gallery

Cube gallery is a justified / Flickr like gallery.

## How to use ?

```js
new CubeGallery(selector, options?).create()
```

### Example

Create a `div` with your images.
```html
<div id="gallery">
    <img src="" alt="">
    <img src="" alt="">
    ...
</div>
```

Instanciate `CubeGallery`.
```js
new CubeGallery('gallery', {
    minHeight: 150
}).create()
```

## Available options

Some options are available to manage your gallery.
```js
{
    minHeight: 100 // default
    margin: 0 // default
}
```
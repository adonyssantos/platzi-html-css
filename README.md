# Image optimization

- SVG to PNG: https://svgtopng.com/
- Image Resizer: https://online-image-resizer.com/
- Compresses the size: https://tinypng.com/
- Remove the metadatos: https://www.verexif.com/
- Others tools:
  - https://compressor.io/
  - https://squoosh.app/

# Responsive design

## Strategy for responsive design:

- Mostly Fluid
- Layout Shifter
- Column Drop

** Media Queries: ** are conditional. It is not the best practice but applying it to the CSS:

```css
@media (min-width: 480px;) {
  /* Code... */
}

@media (min-width: 768px;) {
  /* Code... */
}

@media (min-width: 1024px;) {
  /* Code... */
}
```

** Break Points: ** when the screen is of a certain size, a change will be generated to reposition or resize the containers.

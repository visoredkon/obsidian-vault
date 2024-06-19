```html
<img src="" alt=""></img>
```

Untuk menyisipkan gambar kita menggunakan tag `<img>` yang berarti *image*, link gambar di-input pada *attribute* `src`, sumber gambar dapat dari *internal resource* ataupun *external resource* (*hotlink*).

There are many other attributes to achieve various purposes:
- [Referrer](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Referrer-Policy)/[CORS](https://developer.mozilla.org/en-US/docs/Glossary/CORS) control for security and privacy: see [`crossorigin`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#crossorigin) and [`referrerpolicy`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#referrerpolicy).
- Use both [`width`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#width) and [`height`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#height) to set the intrinsic size of the image, allowing it to take up space before it loads, to mitigate content layout shifts.
- Responsive image hints with [`sizes`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#sizes) and [`srcset`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#srcset) (see also the [`<picture>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) element and our [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) tutorial).
- The `alt` attribute holds a textual replacement for the image, which is mandatory and incredibly useful for accessibility — screen readers read the attribute value out to their users so they know what the image means. Alt text is also displayed on the page if the image can't be loaded for some reason: for example, network errors, content blocking, or linkrot.
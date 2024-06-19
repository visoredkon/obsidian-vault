```html
<a href=""></a>
```

Untuk membuat *hyperlink* kita menggunakan tag `<a>` yang berarti *anchor*, link di-input pada *attribute* `href`, *link* dapat berupa *internal link*, *external link* ataupun *page anchor*, untuk *page anchor* kita perlu mengetahui *id* dari *element* HTML-nya terlebih dahulu kemudian menambahkan *prefix* `#`, contoh: `#element-id`.

*Attributes* lain yang dapat kita gunakan adalah `target`. Where to display the linked URL, as the name for a *browsing context* (a tab, window, or [`<iframe>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)). The following keywords have special meanings for where to load the URL:

- `_self`: The current browsing context. (Default)
- `_blank`: Usually a new tab, but users can configure browsers to open a new window instead.
- `_parent`: The parent browsing context of the current one. If no parent, behaves as `_self`.
- `_top`: The topmost browsing context. To be specific, this means the "highest" context that's an ancestor of the current one. If no ancestors, behaves as `_self`.
- `_unfencedTop`: Allows embedded [fenced frames](https://developer.mozilla.org/en-US/docs/Web/API/Fenced_frame_API) to navigate the top-level frame (i.e. traversing beyond the root of the fenced frame, unlike other reserved destinations). Note that the navigation will still succeed if this is used outside of a fenced frame context, but it will not act like a reserved keyword.
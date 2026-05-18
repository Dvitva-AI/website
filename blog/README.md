# Blog Authoring Guide (HTML)

This blog is now pure HTML for maximum layout control and predictability.

## Add a new post

1. Copy `blog/enterprise-ai-playbook.html` to `blog/<new-slug>.html`.
2. Update title, date, and content in that file.
3. Add a new card in `blog/index.html` linking to the new file.

## Image layout options

Use these classes on `<figure>`:

- Full width: `<figure class="post-image full">`
- Right aligned: `<figure class="post-image right">`
- Left aligned: `<figure class="post-image left">`

Example:

```html
<figure class="post-image right">
  <img src="../logos/edge-logo.png" alt="Example">
  <figcaption>Example caption.</figcaption>
</figure>
```

## Styling

All shared blog styles live in `blog/styles.css`.

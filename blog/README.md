# Blog Authoring Guide

## Add a new post

1. Create a markdown file in `blog/posts/<slug>.md`.
2. Add an entry in `blog/posts.json` with:
   - `slug`
   - `title`
   - `date` (`YYYY-MM-DD`)
   - `excerpt`
   - `cover` (image path)
   - `layout` (`standard` or `feature`)
   - `tags` (array)

## Images in markdown

Standard markdown image:

```md
![My caption](images/my-image.png)
```

Layout modifiers (append to alt text after `|`):

```md
![My caption|full](images/hero.png)
![My caption|right](images/diagram.png)
![My caption|left](images/diagram.png)
```

- `full`: full-width image
- `right`: floating image on right
- `left`: floating image on left

Use `blog/images/` for post assets, or relative paths like `../logos/...`.

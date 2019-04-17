# Contributing

## Writing

Write your article in [kramdown](https://kramdown.gettalong.org/).
Add your writeup to `_posts/`
with the following front matter,
and add a 500x500 cover art under `assets/images/`.

```
---
layout:     post
title:      on Lil Yachty - Minnesota
author:     Ming Li
date:       2017-10-08
categories: lil yachty
album_art:  assets/images/lil_boat.jpg
---
```

Also, we encourage you to embed audio players
from Spotify or Apple Music, or from YouTube
when reviewing a music video.

## Guidelines
- Use a maximum text width of 80 characters for paragraphs
- File names have the format `YYYY-MM-DD-name-here.md`

See [this file](/_posts/2017-10-08-lil-yachty.md) for a complete example.

## Pull requests

Submit a pull request with your new writeup.

```
git checkout -b my-branch
git add _posts/2017-10-08-my-writeup.md
git commit -m "My commit message"
git push -u origin my-branch
```

Your commit messages should be in imperative, present tense
(i.e. "Add sicko mode writeup" instead of "Added sicko mode writeup").

Feel free to add screenshots to verify correctness.

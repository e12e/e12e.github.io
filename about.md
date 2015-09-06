---
layout: page
title: About
permalink: /about/
---

Still just a test site.

### More Information

Adding binary files to the repo requires interacting with git - for that
I still prefer Mercurial. Note-to-self: In order to push to github,
change the `git@github.com/<user>/<repo>` by adding protocol prefix
`ssh+git://` - so that it becomes `ssh+git://<user>/<repo>`. Eg with:

`github = git+ssh://git@github.com:e12e/e12e.github.io.git` in the local
repo `.hg/hgrc`-file, I can simply `hg push github` to update this repo.

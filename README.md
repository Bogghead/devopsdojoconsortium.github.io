# Dojo Consortium Website

This is the source code of the website for devopsdojocommons.org

<a href="https://travis-ci.org/github/devopsdojoconsortium/devopsdojoconsortium.github.io/builds"><img src="https://travis-ci.org/devopsdojoconsortium/devopsdojoconsortium.github.io.svg?branch=release"></a>

---

## Build

```
gem install bundler
bundle install
./native-launch.sh
```

## Contribute

Feel free to [submit pull requests](./CONTRIBUTING.MD)

## [Code of conduct](CODE_OF_CONDUCT.md)

## Adding authors

In `/_data/authors.yml` add your information

## Adding blog posts

In `/_posts/`, Add a new post with the filename matching
`YYYY-MM-DD-post-title.md`

The format should be

```
---
layout: post
author: <your author userid>
---
Blog intro paragraph

<!--more-->

The rest of the blog post after the first paragraph
```

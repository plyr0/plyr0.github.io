# Just my blog

# Gesko

Simple and minimal Jekyll blog by [DavideBri](https://github.com/DavideBri/Gesko).
Forked from [Asko](https://github.com/manuelmazzuola/asko).
Original theme from [Sidey](https://github.com/ronv/sidey).

## Installation

Be sure to have all [you need](https://jekyllrb.com/docs/installation/) before running anything. 

Run local server:

```bash
$ git clone https://github.com/DavideBri/Gesko.git
$ cd Gesko
$ bundle install
$ bundle exec jekyll build
$ bundle exec jekyll serve
```

Navigate to `localhost:4000`. You're Welcome, Fork and be Stargazer.
If you want to upload it to Github Pages, remember to update the `_congif.yml` and if you are going to upload in a repo called yournickname.github.io, remember to update the `{{ site.baseurl }}` to `{{ site.url }}` .
Note that there is also a gtag in the [`_layouts/default.html`](https://github.com/DavideBri/Gesko/blob/6776e4afc384dc3d50ce2001715929c8e70a914c/_layouts/default.html#L9), you should remove it.

To create new tag, create a folder in `tag/` with the name of the new one. In this folder add an `index.html` file and just add this header:
```
---
layout: tag
tag: yourNewTag
---
```
Then build again and you're ready!!

## License

This project is open source and available under the [MIT License](LICENSE.md).

All posts' content is licensed under Creative Commons CC-BY-NC-SA-4.0

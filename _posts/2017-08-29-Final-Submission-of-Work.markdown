---
layout: post
title: "Final Submission of Work"
date: 2017-08-29
categories: jekyll update
---

**The following link will lead to my fork of `matplotlib` branch `artist-traitlets-dev`.  This was the main branch used towards contributions to matplotlib**

[https://github.com/katierose1029/matplotlib/tree/artist-traitlets-dev][https://github.com/katierose1029/matplotlib/tree/artist-traitlets-dev]

*My work can be found in the directory `matplotlib/lib/matplotlib/_traits`*

________________________________________________________________________________

**The following links lead to the pull requests I made**
1. [created new branch and added `_traits` directory with artist.py and tra…][8917]
    * This was the main branch/pull request that displays the process in refactoring `matplotlib.artist.Artist` to `matplotlib._traits.artist.Artist`
    * This refactored module is in terms of [`traitlets`][http://traitlets.readthedocs.io/en/stable/index.html]
    * I accomplished creating a figure using the newly refactored `Artist`
2. [Line2D traitlets dev][9058]
    * After completing the task of drawing a figure using the newly refactored `matplotlib._traits.artist.Artist` module, I set a goal to refactor `matplotlib.lines.Line2D`
    * This took a bit of time to understand how to refactor this module because there were many more attributes and inherited attributes involved. Not only did this module have its own process to follow, but it inherited from `matplotlib._traits.artist.Artist`

________________________________________________________________________________

**This repository was used when I was introduced to the materials/toolkits needed in order to accomplish my goals.  Also I used this repository for scrap code that I did not need at a certain moment but may have needed in the future.**

[gsoc_work][gsoc]

[https://github.com/katierose1029/matplotlib/tree/artist-traitlets-dev]:https://github.com/katierose1029/matplotlib/tree/artist-traitlets-dev
[8917]:https://github.com/matplotlib/matplotlib/pull/8917
[http://traitlets.readthedocs.io/en/stable/index.html]:http://traitlets.readthedocs.io/en/stable/index.html
[9058]:https://github.com/matplotlib/matplotlib/pull/9058
[gsoc]: https://github.com/katierose1029/gsoc_work

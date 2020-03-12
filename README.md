# Learning git

This is Danielle's very exciting summer school repository, which I've created to accompany the Day 2 schedule. The overall schedule of the day is:

- Tutorial on git and GitHub (featuring markdown)
- Introducing R markdown and RStudio projects
- Data wrangling in tidyverse (readr, tibble, dplyr, tidyr)
- Data visualisation in tidyverse (ggplot2)
- Something to do with inferential statistics!

The sections to this document partly accompany the notes...

## Markdown

When introducing git and GitHub, I briefly introduced [Markdown](https://en.wikipedia.org/wiki/Markdown), the "language" in which this README document is written. Markdown is a compact and readable way to create HTML documents, and it is used on GitHub (as a way of creating... README files), but it's also used as one part of R Markdown, which we'll get to later. Some features of Markdown include making lists using `-` (see above).

It's easy to create links to [your favourite website](https://compcogscisydney.org), write *italics* and **boldface**, and even insert images:

![](http://placekitten.com/800/100)

You can comment out things if you don't want them to render. So, for instance, if I decide that I *don't* want to display the puppies that Mathew Ling inserted, I can hide them...

<!--
![Puppies are better than kittens](https://images.unsplash.com/photo-1519150268069-c094cfc0b3c8?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=6e6932150f4fa2cc38e1712f464da47e&auto=format&fit=crop&w=1078&q=80)
-->


... See, no puppies. (Actually, this is useful to note because the way I've done this is by using "raw" HTML. If you know HTML, you can always insert that into a Markdown document)

Headings are created with the `#` character. A line that beings with `#` is a first level heading, a line that begins with `##` is a second-level heading, and a line that begins with `###` is a

### third level heading

Surprising, right? You can insert block quotes using `>`:

> "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."

and you can create `inline code` using backticks, or

```
print("actual code sections")
```

Plus a lot of other things, like adding animated GIFs...

![Adding gifs](https://github.com/ropenscilabs/learngganimate/raw/master/transition_reveal/transition_reveal_files/figure-markdown_github/unnamed-chunk-3-1.gif)

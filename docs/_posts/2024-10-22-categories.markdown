---
layout: post
title: Blog Theme
tags: journal technical
---
# Blog theme
A blog needs a theme.

This blog will have many themes.

Or categories, since I personally associate theme with a color theme
in my editor/terminal/whatever.

One category is probably just journal entries. I need somewhere to
collect my thoughts, this is that category.

Another is technical, how to blog, and programming stuff. In my work I
read a lot (!) and I also write some. I want to become better at
writing, so there's that.

I also want to write about role playing games.

## Technical

I started out putting my headers in HTML tags, but this is markdown!

In Jekyll we differentiate between `tag`, `tags`, `category`,
and `categories`:

```markdown
---
title: Blog categories
tags: journal technical
tag: this will all be one tag
categories: multiple categories
category:  this will all be one category
---
```

But the really useful Jekyll feature is to create directories and let
that decide on the different categories (nice).

That means that the post's file path decides the category:

```
roleplaying/symbaroum/_posts/2024-10-22-good-and-bad.markdown
```
All the directories leading up `_posts` will decide the categories!

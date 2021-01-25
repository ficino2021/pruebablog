---
layout: post
title: Next Steps
tags: second markdown example
categories: demo
---

This is a paragraph in my second post.
In Markdown, adding an image looks similar to a link. 

![alt text is white cat](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/VAN_CAT.png/480px-VAN_CAT.png)

I found this [Cat image on Wikimedia](https://commons.wikimedia.org/wiki/File:VAN_CAT.png).

Horizontal rule:

--------------

> A block quote.
> Is like this.

A table:

| header | column a | column b |
| --- | --- | --- |
| dogs | 3 | 6 |
| cats | 3 | 6 |
| muffins | 15 | 30 |

Posts, Collections, & Pages
Of course not every website is a blog. The _posts directory is completely optional. Posts are optimized to simplify writing blog-like content with features like date, title, and categories built into the filename convention.

Collections provide another flexible option for creating groups of content that can be sorted and iterated over using built in methods (Posts are in fact a specialized, built in Collection).

However, many sites will use only Pages for content.

We have already created index.md, so let’s create the other essential, an About page.

Create about.md
On your repository’s home page, click the “Add file” button and select “Create new file”.
Type in the name for your file: about.md
Create your about with front matter and Markdown following the example below.
Fill in your “commit message” and click the green “Commit changes” button.
---
layout: page
title: About
---

Some Markdown content describing your site.

## About About Pages

The About page is a common convention found on websites.
It is your opportunity to let us know all the details "about" your project:

- focus and topic area
- people involved
- code and projects used

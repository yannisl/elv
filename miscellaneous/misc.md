# INSTALLATION

## Getting Started

You will need a few things.

1. [Download Git](https://desktop.github.com/) 
2. [Download Rust](). On Windows, Rust additionally requires the C++ build tools for Visual Studio 2013 or later. The easiest way to acquire the build tools is by installing Microsoft Visual C++ Build Tools 2015 which provides just the Visual C++ build tools. Alternately, you can [install](https://code.visualstudio.com/) Visual Studio Code. The latter is good as you can also have a good
text editor for editing the content of your book.
3. [Download mdbook](https://github.com/azerupi/mdBook)
4. [Download ngrok](https://ngrok.com)

Make sure you add everything to your path.

You can use any editor of your choice [sublime](https://www.sublimetext.com/3) is not a free one, but I would recommend it, if you are going to delve a bit more into programmming.

## What is mdbook

This is a command line tool created with Rust to create online books using [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files. It is very similar to Gitbook but written in [Rust](https://www.rust-lang.org). These books are actually static websites, like the one you are reading here.

## Going online

The best option is to write a small script to upload the static website to [aws s3](https://aws.amazon.com/s3/), or use [ngrok](https://ngrok.com). See also a good article at [atlassian](https://developer.atlassian.com/blog/2015/05/secure-localhost-tunnels-with-ngrok/).  With ngrok is much easier and quicker, while you developing the content. Also if one is going to get some help for typing the content.

If you change a file, you might have to refresh the browser to see the changes properly.


## Learn a bit of Markdown

By remembering just a bit of mark-up, you can create great online books fast with very little effort. 

Markdown | Less | Pretty
---      | ---  | ---
*Still*  | `renders` | **nicely**
1 | 2 | 3

## Embedding a Video

You can embed a video from youtube or from your own clips, easily using. This can be invaluable when we 
report progress and we can show short clips to transmit ideas better.

```
<iframe width="560" height="315" src="https://www.youtube.com/embed/K5KAc5CoCuk?list=RDF3wpq-i150c" frameborder="0" allowfullscreen></iframe>
```

This will render as follows:


<iframe width="560" height="315" src="https://www.youtube.com/embed/K5KAc5CoCuk?list=RDF3wpq-i150c" frameborder="0" allowfullscreen></iframe>





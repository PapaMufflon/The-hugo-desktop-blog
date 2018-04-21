---
title: "New editor - wooohooo"
type: "post"
date: 2018-04-21T14:42:40
draft: true
---
After being limited with the simple textbox I used before for entering text, I decided to switch to an alternative.

## Monaco text editor

That was a hard fight getting the [Monaco Editor](https://github.com/Microsoft/monaco-editor) to work with this electron-vue-application. In the end, everything looks simple, but these are the best and hardest solutions ;)

So let me show you the present state of the editor-view:

![the integrated monaco editor](https://res.cloudinary.com/alsnuff/image/upload/v1524314983/The-hugo-desktop-blog/New%20editor%20-%20wooohooo/monaco-editor.png "the integrated monaco-editor")

With it come all the bells and wistles Microsoft and other open source developers integrate into this piece of software: syntax highlighting, line numbers, a mini map and a lot of options for me to extend it. I'm planning for a Markdown dummy-modus to convince even the die-hard wordpress fans to switch over :D

## Open blog

Another rudimentary function done. It is now possible to open an existing blog. At least if it has its posts in the /content/posts folder - only those will be shown right now o.O
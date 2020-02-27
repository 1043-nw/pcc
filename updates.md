---
layout: default
title: Updates
---

Some of the libraries featured in the book have been updated recently, which is a good thing - it means you're learning to use Python packages that are steadily being improved. When packages are updated you have the option of using the version that was featured in the book, which lets you run code exactly as it's written in the book. You can also choose to install the latest version of each package, and modify the code in the book slightly. Each approach is outlined clearly in these updates.

[Chapter 10](chapter_10/README.html)
---

Some of the files from Project Gutenberg have a different encoding now. This can result in a decoding error when you try to open the file and read the contents. To address this, we add an argument to the `open()` call.

[Chapter 15](chapter_15/README.html)
---

Pygal has been updated to version 2. You can install a version of Pygal that runs the code exactly as it's written in the book, or you can install the latest version of Pygal and modify what's in the book slightly. See [installing Pygal](chapter_15/README.html#installing-pygal).

[Chapter 16](chapter_16/README.html)
---

Pygal's world map and internationalization features have been moved to a separate module, and there's a slight change to Exercise 16-1. See the section on [installing Pygal](chapter_15/README.html#installing-pygal), and see the specific [updates for Chapter 16](chapter_16/README.html#updates).

[Chapter 17](chapter_17/README.html)
---

The second half of the chapter focuses on a chart representing the most popular Python projects on GitHub. One of the projects that appears on the chart currently has been removed, but still appears in the results. This causes an error, but there's a [simple fix](chapter_17/README.html). Also, the font size settings have been moved from `config` to `style`.

[Chapter 18](chapter_18/README.html#updates)
---

Django 2.0 was released recently, and there are a few changes that affect the Learning Log project. There's a small change to how foreign keys are defined, URLs are specified in a cleaner way, and an import path changed. You also have the option of using Django 1.11 if you'd like.

[Chapter 19](chapter_19/README.html)
---

The changes introduced in Django 2.0 affect some of the code in chapter 19 as well.

The changes introduced in Django 2.1 affect the way user logins and logouts are handled.

[Chapter 20](chapter_20/README.html)
---

The process of deploying a Django project to Heroku has changed slightly. The build process runs from a temporary directory, so the `if` statement in *settings.py* needs to check for this directory as well. Also, there's an improved way of managing static files that you might want to use. See the [updates for Chapter 20](chapter_20/README.html#updates).

Questions
---

If you have any questions about something that doesn't seem to be working in the book, please let me know!

Email: [ehmatthes@gmail.com](mailto:ehmatthes@gmail.com)

Twitter: [@ehmatthes](http://twitter.com/ehmatthes/)

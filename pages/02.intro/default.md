---
title: Intro
hide_title: true
---

# Welcome to grav grama skeleton

Congratulations! You have installed **skelgrama** the grav skeleton that uses the [grama](https://framagit.org/squeak/grama) theme to build **multilingual** websites.

Many pages in this example skeleton are not translated and are displayed in the default english locale. You're welcome to contribute to propose translations and I'll be happy to include them.


### Edit pages

This site gives a small overview of the possibilities offered by the [grama theme](https://framagit.org/squeak/grama). There are quite a few different templates you can use.
A full documentation on how to use `grama` is available [here](https://framagit.org/squeak/grama/-/blob/master/README.md), but this site skeleton should already present quite a few features and customizations available.


### Create a New Page

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `03.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/03.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: The page will automatically show up in the Menu after the "Typography" menu item. If you wish to display a different title in the page than in the menu, you can set `hide_title: true` in header, this will hide the title header in the page, you can now set a title the way you want in your page content. Look at this page code for an example.

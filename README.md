# tonydesign-jekyll

TonyDesign GitHub Pages 主题

Demo 地址：[https://phodal.github.io/mifa-jekyll/](https://phodal.github.io/mifa-jekyll/)

使用方式，在 GitHub Pages 里创建 ``_config.yml`` 文件，并添加以下的内容来启用 Mifa 主题：

```yml
remote_theme: CoderTonyChan/tonydesign-jekyll
google_analytics:
background-image: http://sf6-tccdn-tos.pstatp.com/obj/tuchong-avatar/h_2301626_1
images: 
    - title: 爱人
      src: 'https://photo.tuchong.com/2301626/ft640/209322359.jpg'
      w: 1024
      h: 683
    - title: 爱人
      src: 'https://photo.tuchong.com/2301626/ft640/209322359.jpg'
      w: 1024
      h: 683
    - title: 爱人
      src: 'https://photo.tuchong.com/2301626/ft640/209322359.jpg'
      w: 1024
      h: 683
```

## tonydesign-gallery-theme



## Customizing

### Configuration variables

Cayman will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).


## License
---

<!-- [![CoderTonyChan's Idea](http://brand.phodal.com/shields/idea-small.svg)](http://ideas.phodal.com/) -->

<!-- [![CoderTonyChan's Design](http://brand.phodal.com/shields/design-small.svg)](https://www.phodal.com/) -->

© 2019 A [CoderTonyChan](https://tonystudio.ml)'s [Idea](http://github.com/CoderTonyChan/ideas).  This code is distributed under the MIT license. See `LICENSE` in this directory.

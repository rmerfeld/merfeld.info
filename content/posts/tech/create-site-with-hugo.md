+++
title = "Create a Website with Hugo"
description = ""
date = "2019-01-08"
slug = "" 
categories = ["tech"]
tags = ["web", "jamstack", "hugo"]
draft = false
+++

# Create a Website with Hugo

[Hugo](https://gohugo.io) is a powerful static website generator with a bunch of nice [themes](https://themes.gohugo.io/). So why not start using it for your own website.

``` bash
hugo new site merfeld.info
cd merfeld.info; git init
```

A good starting point for a blog could be the [hugo-coder](https://themes.gohugo.io/hugo-coder/) theme.
Cause it's lean and clean.
Add luizdepra's [github repo](https://github.com/luizdepra/hugo-coder.git) as a submodule to your project.

``` bash
git submodule add https://github.com/luizdepra/hugo-coder.git themes/hugo-coder
cp -r themes/hugo-coder/exampleSite/* .
```

Start hugo's build in server and check the site on http://localhost:1313

``` bash
hugo server -D
```

For more Information about building websites with Hugo, you can have a look into Hugo's [Documentation](https://gohugo.io/documentation/) or start some nice tutorial on [Mike Dane's](https://www.youtube.com/channel/UCvmINlrza7JHB1zkIOuXEbw) youtube channel.

{{< youtube qtIqKaDlqXo >}}
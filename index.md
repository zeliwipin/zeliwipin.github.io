---
permalink: /
title: Jekyll Minimalist
---

by [Roman Zolotarev](https://www.romanzolotarev.com/)

This is an minimalist website boilerplate powered by [GitHub Pages][pages].
There are just [three small files][source].

You can create your own website like this in few minutes without installing
anything or touching command line. All you need is your GitHub account (or
email) and few minutes.

# Quick Start

1. [View source of this site on GitHub][source].
1. Click on **Fork** button.
1. You may need to **Sign in** (or **Create an account**).
1. Go to **Settings** of your new repository and rename it to
   `USERNAME.github.io`, where `USERNAME` is your username on GitHub.
1. Check (on **Settings** page) that **GitHub Pages** is enabled.
1. Your site should be available at `http://USERNAME.github.io/`.

# Add your pages

1. Click on **Create new file** in your new repository.
1. Type-in file name, e.g. `about.md`
1. Put some file content like this:

```
---
title: About
---

This site is about nothing.
```

It is important to use front matter with `title` in every file. The new page
should be available at `http://USERNAME.github.io/about` (based on its
file name).

# Custom domain (optional)

Add `CNAME` file to your repository with your domain name. For example:

```
www.romanzolotarev.com
```

Then add `CNAME` record to DNS zone of your domain that points to
`USERNAME.github.io`. For example:

```
;; CNAME Records
www.romanzolotarev.com. 300 IN  CNAME romanzolotarev.github.io.
```

Now your site should be available at your domain name. In case of those
examples at `http://www.romanzolotarev.com/`.

# Install on your computer (optional)

GitHub Pages uses Jekyll to do all this magic. If you are familiar with git,
then you may want to install GitHub Pages (with Jekyll) on your computer. So
you will be able to edit your pages locally (e.g.  when you are offline) and
view your site locally before publishing.

For example to install on Mac run this command:

```
gem install github-pages
```

Then clone your repository and run Jekyll locally.

```
git clone https://github.com/USERNAME/USERNAME.github.io
cd USERNAME.github.io
jekyll serve -w
```

While Jekyll is running, open <http://localhost:4000/> in your browser. Your
site should be there. You can add and edit pages and Jekyll will automatically
regenerate HTML files, just reload the page in the browser to see changes.

[Learn more about Jekyll][jekyll].

[jekyll]: https://jekyllrb.com/docs/home/
[pages]: https://pages.github.com
[source]: https://github.com/romanzolotarev/jekyll-minimalist
[md]: https://guides.github.com/features/mastering-markdown/

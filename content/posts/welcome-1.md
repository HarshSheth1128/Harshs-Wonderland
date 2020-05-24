---
title: "🤗 Welcome to my blog! 👋🏽"
categories: ["Life", "Tech"]
tags: ['Hugo', 'Static Site Generator', 'Github Pages']
date: 2020-05-16T15:59:43-04:00
draft: false
---

# What is this?

Software engineering is quite a beautiful journey, along the way you learn many different things that strenghten your prowess as a developer to be able to work quickly and efficiently.

This blog serves as a diary of my journey as a developer. I want to share some cool tips and tricks that I've learned over the years, and this seems like the best way to do it!

Many people blog on platforms such as medium, but what appeals to having my own blog is the sense of individuality that comes with it.

## Why Hugo?

I chose the Hugo static site generator over writing a custom site generator on my own for a few reasons.

### Time is money

In my opinion, the best way to learn anything is to do. Furthermore, I like to do without help. Sometimes there is pressure to engineer everything on your own, however using somthing like a SSG greatly reduces the amount of work that I need to do to be able to catalogue my thoughts.

### Speed is important

As a developer this is a tendency to overengineer and reinvent the wheel, however Hugo is a trusted static site generator written in `Go` and is blazing fast. Furthermore, the ability to have hot reload without writing a module to translate markdown documents into markup is phenomenal.

### Quick easy continuous deployment

With how easy it is to use Github pages to host static sites, Hugo was a no brainer first choice. With Hugo all I have to do to get this site deployed is

```bash
# Build the site
hugo -D
# Add to git and commit the new build
git add .
git commit -m 'New Blog Post'
```

It's as easy as that! The `.toml` is configured to deploy to the `/docs` folder which is then set as the source on github.

I hope that anyone reading this blog gets something out of it. Personally I have learned a ton of new things from looking at tutorials and reading comparisons of technologies and I believe that a democratized internet allows us all to get better together!

I hope to see you again here in the future!

---
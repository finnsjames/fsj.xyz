---
title: All New Site
date: 1625976000000
snippet: Now it's all spacey, and has a dark mode
---

# {title}

As much as Jekyll + GitHub Pages served me well for my old static site, I have
decided to take the plunge into a modern framework-based version. This site is
made in the excellent [SvelteKit](https://kit.svelte.dev/). It isn't done, yet.
At time of this writing, the "Posts" page still needs
some work. With that said, I am very happy with how the new site is working out.

I made a point with this rewrite to use as little code from the original version
as possible. The only elements brought over are the SCSS that generates the
Markdown-esque header markers and the click-to-copy email button on the home
page.

The new version of this site is hosted on [Vercel](https://vercel.com/), using
the shockingly simple-to-use Svelte-Vercel adapter. I've been really impressed
with how simple and easy Vercel is to use.

## Why SvelteKit?

I have been wanting to learn to use Svelte for a while now. I've been using Vue
for over a year now, and while I really like its functionality and wide support,
I also like Svelte's opinionated approach to organization and syntax.
Furthermore, I wanted to try a static site generator framework and with
SvelteKit nearing a 1.0 release, I figured now was as good a time as any.  

Next (lol) on the docket are Next.js and Astro.

## So what's left?

I am trying some new stuff with this site. I want to add a lot more details
before I really consider it to be "done." One big example is dark mode support.
I would like to be able to choose "Auto" in addition to the current Light/Dark
toggle. Another one (as I mentioned above) is that I want the blog section to
get some more attention. It's pretty basic right now, which is fine, but I want
to enable photos, code snippets, interactive elements, searching articles, etc.
I also think it would be cool to have some sort of dashboard for editing my
site. Right now the whole site is made by me, so I'd either have to find a
dashboard/CMS to connect up or write my own. In the mean time I suppose I'll be using just VSCode.

---
title: Try to run your Jamstack with 11ty!
description: 11ty is the best static site generator for simple website or blog.
date: 2021-08-10
tags:
  - jamstack
  - 11ty
  - javascript
  - ssg
layout: layouts/post.njk
---
I spent a lot of time trying to deep dive at different static site generators to find the best one for my needs. I wanted to run my own blog and to have possibility to create pretty simple minimalistic websites that will be super easy to manage and will be super fast. To be honest, I'm lazy and I wanted to find perfect solution that will need less job done and will be the easiest way to create such websites.

I've tried [Gatsby](https://www.gatsbyjs.com/), [Next.js](https://nextjs.org/), [VuePress](https://vuepress.vuejs.org/) and some others. But after all my investigations I was really surprised to discover [11ty](https://www.11ty.dev/). Looks like it is exactly what I looking for!

I have a lot of thoughts and feelings about it, so I will try to give you some reasons to run it.

## Why you should try it:

### It is JavaScript

If you are reading this post I believe that you are person who is familiar with the JavaScript and frontend development (it will be little bit strange if you aren't) or you should be the person who is interested to try it. It is a big advantage to use JavaScript-based static site generator. Also you don't need to know React, Angular or Vue, I was surprised, but without all that modern frameworks it going easy and simple as it is possible. I have commercial experience with all of them, but I'm feeling great not using them here.

### Really fast

Very fast builds and very fast pages after the build. Also it is provides **zero client-side JavaScript**! Yeah, there will be missing some very modern features from the box, but all in all you'll can add them if you'll need by yourself. Can you imagine site without JavaScript in our days.!?

### Supports incremental builds

11ty won't rebuild your whole site after changing one file. It will write only the file that was changed. This makes a great developer experience and keeps 11ty fast.

### Works with multiple template languages

You can pick one or use them all together in a single project:

- [HTML `*.html`](https://www.11ty.dev/docs/languages/html/)
- [Markdown `*.md`](https://www.11ty.dev/docs/languages/markdown/)
- [JavaScript `*.11ty.js`](https://www.11ty.dev/docs/languages/javascript/)
- [Liquid `*.liquid`](https://www.11ty.dev/docs/languages/liquid/)
- [Nunjucks `*.njk`](https://www.11ty.dev/docs/languages/nunjucks/)
- [Handlebars `*.hbs`](https://www.11ty.dev/docs/languages/handlebars/)
- [Mustache `*.mustache`](https://www.11ty.dev/docs/languages/mustache/)
- [EJS `*.ejs`](https://www.11ty.dev/docs/languages/ejs/)
- [Haml `*.haml`](https://www.11ty.dev/docs/languages/haml/)
- [Pug `*.pug`](https://www.11ty.dev/docs/languages/pug/)

My favorite is Nunjucks, but you can pick yours favorite. From my perspective Nunjucks keeps everything clean and beautiful.

### Works great with data

You can use internal and external sources of data. Really, it is simple to use external data without any problems.

## Conclusion

I'm 100% sure that this list is not full. I'm new with the 11ty, but I was really exited about its features and how it is working. I found that it is the best SSG for me. Also I believe that 11ty has disadvantages too (everyone has). But I need to use it more deep to know about them more. It is just fast expression about it and I will update that post or will create another one if it will be a lot of things to share.


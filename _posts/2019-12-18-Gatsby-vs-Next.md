---
layout: post
date: 2019-12-04
category: Technology 
description: Web Pages Vs. Web Applications
---


# Gatsby Vs. Next.js
### Web Pages Vs. Web Applications

<br/>
## What are they?
<br/>
They are React Frameworks that out the box:
* Creates blazing fast sites.
* Creates Single Page Apps with ease.
* Gives you great SEO.
* Amazingly documented + easy to use.React sites has never been easier.

<br/>
## Gatsby: 
<br/>
A static site generator.

Generates all the HTML at build time so I'd does not require a server at all. The entire site can be placed in an S3 bucket. Or in Azure Storage for hosting. (This is far cheaper than running a server constantly)

Gatsby is very scalable in terms of high traffic, as we are just delivering already pages.

Gatsby dictates how to handle your data - using GraphQL. Which is an amazing tool, which can really speed up development in some use cases.

Plugins in Gatsby really improves developer experience, there are many plugins available that provide an immense amount of 

Cons of Gatsby is that it may not scale well with a site with a LOT of content,as building the entire site may take a while. Gatsby may also not be what you want when you want client side fetching data / real time content updates.

However, Gatsby are soon to be releasing incremental builds, only rebuilding updated content will save an incredible amount of build time.


<br/>
## Next.js:
<br/>
Typically Server Side Rendering, however it supports static site pages. 

Next.js is actually quite flexible with how you deliver data, it is very easy to choose between client side rendering / server side rendering / static site pages

Next.js requires a server ( Extra costs ), but this means that the content can be dynamic, live content updates are possible, and client - server interactions are possible.

Next.js does not dictate how to handle your data, you can choose completely how to do this yourself, you can even decide to use GraphQL if you so wish.

For sites with a large amount of content / with any client - server interactions, Next.js is the choice to make. As a server-side site it will be completely scale-able to however large the content is.



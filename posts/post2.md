---
layout: base.njk
title: "Web bloat: a case for lean design"
date: 2026-10-13
tags: post
---

Spinning up a simple portfolio or personal blog shouldn't require an enterprise-grade cloud architecture, three state management libraries, and 50 megabytes of client-side JavaScript. Yet, modern web development has quietly normalized a culture where performance and simplicity are constantly sacrificed for developer convenience.

We have built a web that is heavier, and slower than ever before; it's time to make a case for lean design.


### The Hidden Cost of Modern Bloat

As creative developers, we love interactivity, movement, and expressive layouts. But somewhere along the line, the tools we picked up to build these experiences started consuming them.

Today, a typical user visiting a modern website downloads megabytes of script bundles before they can even read a sentence. The consequences are real:

- **Lost Craftsmanship:** When every interaction relies on heavy UI abstractions, developers stop mastering raw platform primitives like CSS, semantic HTML, and browser APIs.
- **Performance Degradation:** Mobile CPUs struggle under the weight of continuous re-renders and heavy hydration processes.
- **Fragile Architecture:** Deep dependency trees mean a single breaking change three layers down can break an entire UI.

Bloat isn't just an engineering inconvenience—it harms user experience and degrades the web as a shared canvas.


### My Preferred Stack

Building lean doesn't mean building boring, plain-text pages stripped of delight. It means choosing tools that do their heavy lifting at build time or focus strictly on their single responsibility.

To stay fast without sacrificing dynamic, creative motion, my stack relies on four lean building blocks:

- **CSS3:** Modern CSS features like container queries, grid, native nesting, and CSS variables eliminate the need for bloated utility frameworks or heavy preprocessors.
- **SvelteKit:** Compiles reactive components down to minimal vanilla JavaScript at build time. No bulky virtual DOM overhead in the browser.
- **GSAP:** Provides precise, high-performance animation timelines and smooth scroll interactions without triggering layout thrashing.
- **11ty:** Generates zero-JS static HTML by default for content pages, delivering instantaneous page loads.

By stripping away the unnecessary runtime baggage, the site loads instantly, animations run at a locked 60 FPS, and every kilobyte serves a clear purpose.


### Reclaiming Developer Joy

When you stop managing massive build configurations and chasing framework updates every few months, something remarkable happens: you get to focus on crafting great experiences again.

Lean web design is a commitment to intentionality. It asks simple questions before adding any dependency: *Does this serve the user? Can the web platform do this natively? Can we build this simpler?*

> The web doesn't need more tools to be dynamic. It needs more intentional engineering.


### Conclusion

Building fast, lightweight web experiences is all about respecting the user's attention, device, and data, while enjoying the pure craft of building on the web.

If we want a better, faster, and more creative web, we have to start by shipping less bloat.
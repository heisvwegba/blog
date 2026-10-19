---
layout: base.njk
title: "The modern web is bloated"
date: 2026-09-18
tags: post
---

The modern web has become ridiculously over-engineered, trading lightweight user experiences for sprawling developer frameworks, but a return to simplicity is both necessary and totally achievable.


### Tool Bloat / Over-Engineering

Somewhere along the line, web development went from building simple digital front doors to constructing sprawling, multi-layered skyscrapers just to deliver a recipe for chocolate chip cookies.

Today’s standard tech stack often looks like a stack of bricks that keeps getting taller:

* **Frameworks on frameworks:** We build React apps wrapped in Next.js, powered by Tailwind, bundled with Vite, and managed by dozens of dependencies.
* **The node_modules black hole:** A single empty project can pull in thousands of packages before you’ve written a single line of original code.
* **JavaScript everywhere:** Pages that could easily be static HTML now rely on heavy client-side JavaScript execution just to display plain text.

We’ve swapped simplicity for convenience, building complex pipelines for problems that didn't always exist.


### Consequences for the User

Developers get cool tools, but what about the actual human being sitting on the other side of the screen?

* **The Dreaded Loading Spinner:** Millions of lines of JavaScript mean longer load times, high memory usage, and fans whirring on laptops like jet engines.
* **Data-Heavy Browsing**: Downloading 15MB of scripts, tracking pixels, and auto-playing video ads just to read a 300-word article burns through mobile data plans fast.
* **Inaccessible & Fragile:** When everything relies on complex client-side rendering, one broken script or bad network hop can result in a blank white screen.
* **Battery Drain:** Processing mountains of unnecessary JavaScript constantly keeps device CPUs working overtime, draining mobile batteries far faster than simple web pages ever did.
* **Layout Shift Chaos (CLS):** Heavy scripts loading in asynchronously cause text and buttons to jump around the screen right as you're trying to click, leading to accidental misclicks and user rage.
* **Exclusion on Older Hardware:** Sites optimized only for high-end developer laptops leave users on budget phones or older computers behind, creating a digital divide powered by bloat.
* **Privacy Violations:** Half of that bloat isn't even for rendering the page. It's trackers, telemetry, and ad networks quietly watching every scroll and hover.


### A Better Web

The good news? We don't have to keep building this way. A lighter, faster web is already making a quiet comeback.

* **Embrace Static First:** Tools like Astro, Eleventy, and HTML/CSS-first approaches show that static content can (and should) stay static.
* **Less Is More:** Using native browser features instead of pulling in huge third-party libraries for basic UI elements.
* **Focus on Performance:** Treating web performance as a core feature rather than an afterthought.


### Conclusion

The modern web doesn't need to be this heavy. By stepping back from extreme over-engineering and prioritizing lightweight, user-focused design, we can make browsing fast, fun, and effortless again. Let's make the web lightweight again!
---
title: CCAT Group website
publishDate: 2022-03-02 00:00:00
img: /assets/ccat.png
img_alt: Passenger plane parked on a runway with a sunset
link: https://github.com/CameronMackenzie99/ccatgroup
description: |
  I developed a static site for a new aviation consultancy, to serve as a landing page for their clients.
tags:
  - Astro
  - TailwindCSS
  - Design
---

This site was made for an aviation consultancy who wanted a simple landing page and contact form for their business. It uses an Astro template, with SEO features built in. The Astro framework renders a fully static site, with the ability to "turn on" interactively in certain components using React, Svelte etc. to send a small amount of Javascript to the client. I was going to use this for the contact form, but the form ended up not having complex requirements, so instead it is just a plain HTML form, connected to Netlify with a serverless function to submit the responses. This project solidified concepts around server-side generation, reducing Javascript served to the browser to improve load times.
---
title: Student Loan Tracker
publishDate: 2023-07-07 00:00:00
img: ../../assets/graphs.png
img_alt: A graph from the web app showing total repaid and loan balance over time.
link:  https://student-loan-tracker.vercel.app
description: |
  I built a web app to visualise student loans, to give prospective students confidence in their financial decisions.
tags:
  - React
  - Next.js
  - TailwindCSS
---

> From 2023, new students will be making payments for 40 years, a change that needs attention. 

Student loans are now a more consequential financial decision, and it is increasingly difficult to assess the value of a student loan. The web app projects loan balance, with interactive editable rows and graphs showing nominal vs real data, to allow visualisation of future payments. 

I took a mobile-first approach when designing the layout using TailwindCSS's responsive design paradigms to ensure accessibility. I continue to add features from feedback and plan to promote the website online after adding the remaining MVP functionality.

The calculation inputs form uses <a href="https://zod.dev/">Zod</a> validation on the client, which integrates seamlessly with <a href="https://react-hook-form.com">React Hook Form</a> to provide a fully type-safe form. 

I plan to use tRPC when adding in saving and user account functionality, in order to save projections across sessions and track loans over time.
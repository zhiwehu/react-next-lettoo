---
title: 'Using Strapi as backend for quick development'
date: '2021-12-21'
lastmod: '2021-12-21'
tags: ['react', 'strapi', 'development']
draft: true
summary: 'As a full stack developer we should know both backend and frontend. For now using React as frontend is quite popular. I suggest using Strapi as backend so that we can have a quick headless CMS backend which provide REST or GraphQL method, include user auth and role permission functions. And it is open source so you can change code by self if needed.'
images: []
authors: ['default']
layout: PostLayout
---

As a full stack developer we should know both backend and frontend. For now using React as frontend is quite popular. I suggest using Strapi as backend so that we can have a quick headless CMS backend which provide REST or GraphQL method, include user auth and role permission functions. And it is open source so you can change code by self if needed.

## strapi

https://strapi.io/ is a open-source headless CMS which promo "Design APIs fast, manage content easily." I found it's really handy for quick development especially for MVP project. It's built by JavaScript so it's easilly for JavaScript frontend developer usage.

### Installation

Install the strapi project is very simple. Open the terminal window, and goto a directory you want to store the strapi project. Make sure you already installed Node.js, then run the command as below:

```shell
yarn create strapi-app your-project-name --quickstart
```

> I found it'll throw an error message if I try to use `npx` command to install the strapi. I did a quick research and it seems there's a known issue related Node.js 16.x version. `yarn` is good for this Node.js version.

### Configure the super admin account

Once the installation is complete, the browser automatically opens a new tab to let you fill the super admin info.

![image-20211221123316782](../../../../../../Library/Application Support/typora-user-images/image-20211221123316782.png)

### Build a quick frontend signup to use strapi

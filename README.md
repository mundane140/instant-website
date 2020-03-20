# Instant website
> Manifest a business idea as a simple webpage - using custom text and images supplied in a URL and no coding.

[![Netlify Status](https://api.netlify.com/api/v1/badges/8f1fc5a5-1b67-4d14-94c6-512c4eacdad7/deploy-status)](https://app.netlify.com/sites/instant-website/deploys)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/instant-website.svg)](https://GitHub.com/MichaelCurrin/instant-website/tags/)
[![Made with Node](https://img.shields.io/badge/Made%20with-Node-blue.svg)](https://nodejs.org)
[![Made with React-URL-Query](https://img.shields.io/badge/Made%20with-React%20URL%20Query-blue.svg)](https://www.npmjs.com/package/react-url-query)
[![Made with Bulma](https://img.shields.io/badge/Made%20with-Bulma-blue.svg)](https://bulma.io/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/MichaelCurrin/instant-website/blob/master/LICENSE)

Great for prototyping how a real or fictional business webpage could look like, within the framework of a one-page landing page template.

- Project site: [instant-website.netlify.com](https://instant-website.netlify.com/)


## Features

### What can it do?

- A dynamic website based on your choices.
- Start with a clean one-page landing page template.
- Customize the content and styling
    - Use a form. Custom values are pushed to the address bar.
    - Or change values in the address bar and press enter.
- While you can't save your page, you can share your URL so someone else can see what you see.

### How do I use it?

1. Choose your fields (title, background image, etc.) using a form tool.
2. You will get a URL with your custom values in the [query parameters](https://github.com/MichaelCurrin/learn-to-code/blob/master/Web%20dev/HTML/url_query_parameters.md).
3. Use the URL to view a dynamic webpage which adapts to your values and changes the text and images to match it.
4. Share the URL with others.


## Purpose and background

I was frustrated at the time it takes to create a new website on a whim. I had a flow using a base HTML page or a Jekyll site which a config, but I wanted it to be faster.

Then I realized that a single website can look however I wish it within seconds by using _JavaScript_ to make it dynamic.

So I found a way to build a webpage in the browser, using a template page I created and some URL query parameters to configure it. For ease of use over editing the URL directly, I added a form input which generates the page and the URL. An easy do this is with React.

The appearance of the site is kept simple - some text and some images, with a fixed layout.

### Inspiration for design

- [whoopi-goldbot.netlify.com](https://whoopi-goldbot.netlify.com/)
- [landing-page-boilerplate](https://michaelcurrin.github.io/landing-page-boilerplate/)
- [docsify](https://docsify.js.org/#/) cover page.


## Remote setup

See [Remote](/docs/remote.md) doc.


## Local setup

- [Installation](/docs/installation.md).
- [Usage](/docs/usage.md)
- [Demo](/docs/demo.md) - This focuses on rendering flat content using Bulma styling and does not use React or any other JS.


## Credits

### Bulma card layout

- [CodePen](https://codepen.io/egoens/pen/NbmEbR) of a centered card, made Bulma. This HTML and CSS (specified there SCSS) as was used as the basis for my project's layout.
- Bulma tutorials
    - [Image](https://bulma.io/documentation/elements/image/) element.
    - [Card](https://bulma.io/documentation/components/card/) components.

### React URL Query

- [pbeshai/react-url-query](https://github.com/pbeshai/react-url-query) on Github. After I had the idea to use React to manage the state and push and pull [URL query parameter](https://github.com/MichaelCurrin/learn-to-code/blob/master/Web%20dev/HTML/url_query_parameters.md) data, I soon found this project. I used that project's [basic](https://github.com/pbeshai/react-url-query/tree/master/examples/basic) example as a starting point for this repo. The other examples use React Router, but I didn't want to add another dependency in case it added more complexity than what it reduced, especially if I the basic one works fine without that.

### Images

Stock image used for free from [unsplash.com](https://unsplash.com) and loaded through their [source.unsplash.com]((https://source.unsplash.com) domain.

Read more [here](https://github.com/MichaelCurrin/learn-to-code/blob/master/Web%20dev/stock_images.md).

---
layout: post
title: Adding a Contact Form to My Portfolio
date: 2025-03-03 18:01:00
description: How I added a contact form to my static site.
tags: website, portfolio
categories: portfolio
thumbnail: assets/img/contact.png
---

## Adding a Contact Form to My Portfolio  

![Contact Form](assets/img/contact.png)

Since my portfolio is a static site hosted on GitHub Pages, I can't use a traditional contact form that relies on a backend server. Static sites don’t support server-side processing, meaning forms can't handle submissions on their own.

To work around this, I used an external provider to embed a contact form on the site. Initially, I picked a service that seemed promising, but I overlooked its submission limit—it was far too low for practical use. After some searching, I found a better provider that allows up to **100 submissions per month**, which is reasonable for a portfolio site.

Now, visitors can easily reach out without needing to hunt for an email address. If you're considering adding a form to your own static site, just make sure to check the limits before committing to a service!

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/contact.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Final Result
</div>
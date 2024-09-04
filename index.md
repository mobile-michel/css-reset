---
title: Home
layout: default
tags: primary
date: 2024-01-01
---
## Normalization Libraries

CSS Normalization libraries will provide you with a clean slate, but, unlike CSS Reset libraries, CSS Normalization libraries will provide standardized styling for all elements. For example, your headings should look the same in all browsers, spacing should be normalized, etc. The goal of a normalization library is less about removing all default styling: the focus is to provide a base styling that is consistent across different browsers.

{% assign library = reset | where: 'category', 'normalization' %}
{% for item in library %}
- [{{ item.name }}](/paginate/{{ item.name | slug }}/index.html) by {{ item.author }}
{% endfor %}

## CSS Reset

The purpose of a CSS Reset library is to “reset” all CSS styling to remove default browser styling, sometimes setting default styling that is often used by default. This allows you to start working on your project without worrying about browser inconsistencies, or forgetting to overwrite properties that may have unintended styling. Using a CSS Reset library, all styling set on an element will only be what you defined.

{% assign library = reset | where: 'category', 'reset' %}
{% for item in library %}
- [{{ item.name }}](/paginate/{{ item.name | slug }}) by {{ item.author }}
{% endfor %}

## Articles

[5 Best CSS Reset/Normalization Libraries](https://krdevnotes.com/5-best-css-reset-normalization-libraries/#:~:text=CSS%20Normalization,-Just%20like%20CSS&text=The%20goal%20of%20a%20normalization,is%20consistent%20across%20different%20browsers.)

## Searches

- [CSS Normalization Libraries](https://www.google.ch/search?q=CSS+Normalization+Libraries)
- [CSS reset](https://www.google.ch/search?q=css+reset)
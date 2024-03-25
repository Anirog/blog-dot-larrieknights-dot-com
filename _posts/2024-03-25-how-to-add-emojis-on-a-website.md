---
layout: post
title: How to Add Emojis on a Website
date: 2024-03-25
categories: [HTML]
---

Although not great practice for a company website, I like using emojis for my personal project websites, adding emojis to a website is easy.

## Instructions

### Find the unicode character of the emoji you want to use.
- Go to [emojipedia.org](https://emojipedia.org) and search for the emoji you want (for this example I searched for guitar)
- Under the emoji click the tab 'Technical Information'
- Next to 'Codepoints' you will see the unicode character for the emoji.
- For example the unicode for the Guitar emoji is `U+1F3B8`

### Change the unicode

- Remove `U+` replace it with `&#x`
- Add a semi colon at the end `;`
- So `U+1F3B8` becomes `&#x1F3B8;`

### Add the HTML

- Add `&#x1F3B8;` in the HTML file wherever you want the emoji to be.

## Example

**HTML**

`<p>This is a guitar &#x1F3B8;</p>`

**Will give you:**

![Screenshot of a Guitar emoji](/images/guitar-emoji.png)

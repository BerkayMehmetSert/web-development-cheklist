# HTML Semantics Checklist

### Table of Contents
- [Boilerplate](#boilerplate)
- [Document](#document)
- [Content](#content)
- [Data](#data)
- [No-nos](#no-nos)
- [Validation](#validation)

## Boilerplate

1. [ ] The `<html>` tag has a correct lang attribute.
2. [ ] Includes `<meta charset="utf-8">` immediately after `<head>`.
3. [ ] Includes `<title>`.
4. [ ] The `<title>` is unique for every page—and isn’t “Untitled”.
5. [ ] The `<title>` comes after `<meta charset>`.
6. [ ] CSS files are inside the `<head>`, after the `<title>`.
7. [ ] Contains the meta viewport tag.
8. [ ] No HTML is outside the `<body>` element.
9. [ ] JS files are directly above the closing `</body>`.

## Document

1. [ ] A `<header>` tag is around the website’s masthead.
2. [ ] A `<nav>` tag is around the most important navigation.
3. [ ] A `<main>` element is around the primary content.
4. [ ] A `<footer>` tag is around the copyright notice.
5. [ ] Contains `<article>` and `<section>` tags where appropriate.

## Content

1. [ ] All content has a semantically appropriate element & no content is outside of an element.
2. [ ] There’s an appropriate `<h1>` tag on every page.
3. [ ] Headings are ordered properly.
4. [ ] All links go somewhere.
5. [ ] W3C link checker
6. [ ] The `<figure>` isn’t used without a `<figcaption>`.
7. [ ] All email addresses and phone numbers are linked.

## Data

1. [ ] All dates & times are marked up with `<time>`.
2. [ ] All data points are marked up with `<data>`.
3. [ ] All ranges of numbers are marked up with `<meter>`.

## No-nos

1. [ ] The `<em>` and `<i>` tags are not used to make text italic.
2. [ ] The `<strong>` and `<b>` tags are not used to make text bold.
3. [ ] The `<br>` tag is not used to make space.
4. [ ] The `<hr>` tag is not used to make horizontal lines.

## Validation

1. [ ] The document is perfectly indented.
2. [ ] Every HTML file has been validated.
3. [ ] There’s nothing immediately inside `<ul>` & `<ol>` except `<li>` elements.
4. [ ] No `<li>` tags are outside of `<ul>` or `<ol>`.
5. [ ] The `<figcaption>` isn’t outside a` <figure>`.
6. [ ] There’s nothing immediately inside `<dl>` except `<dt>`, `<dd>` & `<div>` elements.
7. [ ] No `<dt>` or `<dd>` tags are outside of a `<dl>.`
**Before you start:** rename this file to `html12b_SEO_lastname.md`, using your own last name. Watch videos 4–6 and use **Part 2** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**
Ben Devera
---

# Task 12b — Search Engine Optimization (SEO)

Type your answers on the blank line under each **Answer:**, or fix the code inside the code boxes. Explain in your own words where a question asks why.

## 1. How a search engine works

**a.** Put the three steps a search engine uses in order, and describe each one in one sentence of your own.

| Step | Name | What happens |
|---|---|---|
| 1 | Crawl | What other websites yours is linked in |
| 2 | Index | What the page is a bout |
| 3 | Rank | The ranks on how useful it is based of the search |

**b.** You just built a new page, but **no other page links to it**. Why might a search engine have trouble finding it? (Hint: think about how crawlers find pages.)

**Answer:**
The crawlers wont have accsess to it

## 2. Organic vs. paid

**c.** You search for "pizza Medina Ohio." The first two results say **Sponsored**. The next ones do not. Which results are organic and which are paid? Which kind can SEO help with?

**Answer:**
The ones that are not sponsored are organic. SEO help those, sponsored are put at the top result in exchange for paying the browser

**d.** A business owner asks, "Why would I spend time on SEO when I could just pay for ads?" Give one reason SEO is still worth it.

**Answer:**
As useful as ads are they wont procide 100% of traffic, people tend to click on the first few llinks, aswell as over doing it on ads can leave a sour taste in some peoples mouth towards your site.

## 3. Fix the head

This is the `<head>` of a bakery's home page. It works, but it is weak for SEO.

```html
<head>
  <meta charset="UTF-8">
  <title>"Home"</title>
</head>
```

**e.** Rewrite it below. Add a strong `<title>`, a meta description, and the viewport meta tag. Make up a name and town for the bakery.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Bakery, and recipes">
  <title>"Brand's" Bakery</title>
</head>
```

**f.** Where does the text in your `<title>` show up? Where does the meta description usually show up?

**Answer:**
in the page source

## 4. Fix the page

**g.** Rewrite this code to be better for SEO and accessibility. Fix the alt text, the link text, and the file name.

```html
<img src="IMG_4471.jpg" alt="picture">
<a href="page3.html">Click here</a> to see our menu.
```

Your fixed version:

```html
<img src="nameOfFocusedObject.jpg" alt="description of the linked image">
<a href="Menu.html">Click here</a> to see our menu.
```

**h.** A page has three `<h1>` tags: one for the logo, one for the page title, and one for the footer. What is wrong, and how should the headings be set up?

**Answer:**
There should only be one h1 on the page, typically for the page title or main header. The footer and logo should either be lowered, be styled differently in css, or be turned into an image rather than text.

## 5. Spot the problem

**i.** Here is a meta description someone wrote:

`content="cheap shoes cheap shoes best cheap shoes buy cheap shoes cheap shoes near me"`

What is this called? What will a search engine do about it? Rewrite it as a good description.

**Answer:**
A weak choice, the description is too long and is trying to abuse SEO. The search engine will flag it as such and igore it. A better description would be "Buy the best cheap shoes in (location)"

**j.** Name **two** SEO choices that also help people who use screen readers. Explain how each one helps both.

**Answer:**
Alt text, gives an image a description for screen readers to read off.
Heading hiearchy, using proper heading hiearchy allows the user to jump between heading easily with a screen reader while finding what theyre searching for.

## 6. Your own site

**k.** Write a `<title>` and a meta description for the `index.html` of your DIY website. Then add them to your real `index.html` and push it.

```html
<title>
  Htm-Learning, learn web basics
</title>

<  <meta name="description" content="Free html information and help">

```


## Closing 12b — Vocabulary

| Term | Your definition |
|---|---|
| SEO | Search engine optimization, the prosess of web designing to make a website that uses the search engines algorithm properly |
| Crawler (spider) | The part of a search engines alrgorithm that checks what links lead to your page |
| Organic results | Results that show up based off the algorithm in a search engine |
| Meta description | Part of Seo, a short summary of your page and what it does|
| Keyword stuffing | The overuse of certain keywords, typically in an attempt to abuse the search engine's algorithm |
| SERP | The page the search engine makes and gives based of the users search. |
**Before you start:** rename this file to `html12a_Colors_lastname.md`, using your own last name. Watch videos 1–3 and use **Part 1** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**
Ben Devera
---

# Task 12a — Web Colors (RGB and Hex)

Type your answers on the blank line under each **Answer:**. Don't just copy the study guide. Explain in your own words where a question asks why.

## 1. How screens make color

**a.** A screen turns its red and blue lights all the way up and leaves green off. What color do you see? Why is mixing light called **additive** color?

**Answer:**
This creates purple, mixing light is additive color because it increases red greenand blue brightness to make colors, the product color being a mixture of the rgb values 

**b.** A classmate says, "Hex has fewer colors than RGB because hex codes use fewer digits." Are they right? Explain using the number of choices for each color.

**Answer:**
No, hex and rgb have the same values, just adfiferent format

## 2. Reading hex codes

**c.** Name the color for each hex code. For the last two, say whether it is a light or dark gray and how you can tell.

| Hex | Color | Why |
|---|---| ---|
| `#FF00FF` | Purple | Red + Blue = Purple |
| `#00FFFF` | Teal | Green + Blue = Teal |
| `#FFFF00` | Orange | Red + Green = Orange |
| `#CCCCCC` | Light Gray | All values the same = black, gray, or white. Values upper middle = light, but not white, otherwords light gray |
| `#1A1A1A` | Dark Gray | All values the same = black, gray, or white. Values lower middle = dark, but not black, otherwords dark gray |

**d.** In `#3C9F12`, which pair is the strongest? What color family will this be?

**Answer:**
"9F" being 16(9)+1(15)=159, the family is blue

**e.** The CSS color name `lime` and the CSS color name `green` are not the same color. Give the hex code for each.

**Answer:**

Lime = 00ff00

Green = 008000

## 3. Converting between hex and RGB

**f.** Write each color the other way.

| Given | Write it as |
|---|---|
| `rgb(255, 255, 0)` | hex: ffff00 |
| `#0000FF` | rgb:000, 000, 255 |
| `rgb(0, 0, 0)` | hex:000 (Shorthand for 000000)|
| `#FFFFFF` | rgb: 255, 255, 255 |

**g.** Convert the hex pair `C0` to a normal number. Show your work using the rule in section 1.4 (first digit × 16, plus the second digit). Remember C = 12.

**Answer:**
16(12) + 1(10) = 202

**h.** `#F80` is short hex. Write it out as a full 6-digit hex code.

**Answer:**
FF8800

## 4. Colors in CSS

**i.** Write CSS that does both of these. Use **hex** for one and **rgb** for the other.
- Makes `h1` text red
- Makes the page (`body`) background white

```css
h1 {
    color: #ff0000;
}

body {
    background-color: 255, 255, 255;
}

```

**j.** Write a CSS rule for a class called `.overlay` that makes its background **black and half see-through**. Which number controls the see-through part?

```css
.overlay {
    background-color: rgba(0, 0, 0, .5)
}

```

**Answer:**
a, or .5

**k.** Why is yellow text (`#FFFF00`) on a white background (`#FFFFFF`) a bad choice? What would you change?

**Answer:**
Light on light, hrder to read. Either darken the background or text, typically pages use black text

## 5. Your own site

**l.** Open the `styles.css` for your DIY website. Pick one color you used (or choose a new one you like). Write it as a hex code, then explain what the red, green, and blue pairs tell you about the color.

**Answer:**
#389AE5, Very blue, slightly greenish, barely red, will make a light blue

## Closing 12a — Vocabulary

| Term | Your definition |
|---|---|
| RGB | The three string color coding method that uses values 0-255 for Red, Green, and Blue |
| Hex code | The three string color coding method that uses values 1-f in pairs of two for Red, Green, and Blue. a-f = 10-15. Each pair is made of two characters, the left value is mutiplied by 15, then the right value is added. |
| Hexadecimal | A number system that uses base 16 |
| Additive color | The form of color mixing used by light |
| rgba | The four string color coding metho that uses values 0-255 for Red, Green, and Blue, and Alpha (opacity) which use 0-1 instead|
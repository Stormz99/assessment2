# Scissor landing page

A Figma-to-code conversion of the Scissor URL shortener landing page, built with plain HTML and CSS for my AltSchool assessment. No frameworks, no build step, and no JavaScript.

## Running it

Open `index.html` in a browser. That's all.

## What's in the page

Hero, stats, "Why choose Scissors" features, pricing, the URL form, FAQs, a Get Started banner and the footer. The FAQs use `<details>` and `<summary>`, so they open and close without any script.

## Files

```
index.html
styles.css
assets/        SVGs exported from the Figma file, plus a few icons drawn by hand
```

The hand-drawn icons are the check marks, chevron, plus and minus, magic wand, LinkedIn, Facebook and the dark footer logo. They weren't in the exported assets.

## Responsive behaviour

The desktop layout follows the Figma frame at 1440px. The layout changes at 1300px, 1160px, 1130px, 1000px and 600px, and nothing scrolls sideways down to 320px.

## Notes

- The design uses Gilroy, which isn't a free font. Until it's added with an `@font-face` rule, the page falls back to Plus Jakarta Sans, so text can wrap slightly differently from the Figma.
- Most links point to `#`.
- Only the first FAQ answer comes from the design. The rest, and the `scissor.link` domain option in the form, are placeholder text.

# Scissor landing page

This is my AltSchool assessment: the Scissor URL shortener landing page, rebuilt from a Figma design using only HTML and CSS.

Design: https://www.figma.com/design/Ug5dFpdPeyOy1NNAmZxfov/AltSchoolV2-Exam?node-id=1-448&t=mm6ilGIybcyKjDEI-0

To see it, open `index.html` in your browser. There's nothing to install.

The page goes hero, stats, features, pricing, the URL form, FAQs, a Get Started banner and the footer. The FAQs are plain `<details>` elements, so there's no JavaScript anywhere. It works down to phone width.

A few things to know:

- The design uses Gilroy, which isn't free, so I'm falling back to Plus Jakarta Sans. Text wraps a little differently because of that.
- The SVGs in `assets` are from the Figma export. The check marks, chevron, plus/minus, magic wand, LinkedIn, Facebook and the dark footer logo weren't in it, so I added those myself.
- Most links are just `#` for now.
- Only the first FAQ answer is from the design. I wrote the others, and the `scissor.link` option in the form dropdown, as placeholders.

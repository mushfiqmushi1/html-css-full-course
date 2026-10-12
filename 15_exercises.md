# Practice Exercises 🧠

Do these after each lesson. Change the code, refresh the browser, observe.
That's the whole method.

---

## 01 — HTML Basics
1. Create a page with one `h1` (your name), two `h2` sections ("About me", "Hobbies"),
   and a paragraph under each.
2. Add an `hr` between the sections and a comment with today's date.

## 02 — Text, Links & Images
3. Make a recipe page: `h1` title, `ul` ingredients, `ol` steps, and make
   one ingredient **bold** and one *italic*.
4. Add three links: one to any website (new tab), one back to `01_html_basics.html`,
   and one `mailto:` link.
5. Add an image with proper `alt` text, then wrap it in a link.

## 03 — Tables
6. Build a weekly class routine table: days as rows, time slots as columns.
   Use one `colspan` (e.g. "Lunch break" across all columns).
7. Add `thead`, `tbody` and a `caption` to the table from #6.

## 04 — Forms
8. Build a "Contact me" form: name, email, subject (select), message (textarea),
   and a submit button. Every input needs a proper `label`.
9. Add validation: name `required`, email `type="email"`, message `minlength="20"`.
   Try submitting empty — watch the browser stop you.

## 05 — Semantic & Media
10. Convert any page from lessons 1–4 to semantic HTML:
    `header`, `nav`, `main`, `article`/`section`, `footer`. No visual change needed —
    view source should just read better.
11. Embed a YouTube video with an `iframe` (use YouTube's Share → Embed code)
    and give it a `title`.

## 06 — CSS Basics
12. Style the recipe page from #3 using ONLY classes: color the title,
    give ingredients a light background, highlight one step with `:nth-child`.
13. Explain in a comment: why did you use classes instead of IDs?
14. Make all links turn red on `:hover` and show a focus outline on inputs.

## 07 — Box Model
15. Create three boxes side by side using `inline-block`, each 150px wide
    with 20px padding — use `box-sizing: border-box` so they stay 150px.
16. Center a 400px-wide card with `margin: 0 auto`.
17. Remove `box-sizing: border-box` temporarily and observe what breaks. Put it back!

## 08 — Flexbox
18. Build a navbar: logo left, 3 links center, login button right
    (hint: `justify-content: space-between`).
19. Center a login form perfectly in the viewport using flexbox
    (hint: `min-height: 100vh` on the parent).
20. Make a row of 4 cards where the 2nd card is twice as wide (`flex-grow`).

## 09 — Grid
21. Build a photo gallery with `repeat(auto-fit, minmax(200px, 1fr))` —
    resize the window and watch it reflow.
22. Recreate this layout with `grid-template-areas`:
    ```
    header header header
    nav    main   ads
    footer footer footer
    ```
23. Make one gallery item span 2 columns AND 2 rows.

## 10 — Positioning
24. Add a "back to top" button `fixed` at the bottom-right of the landing page.
25. Make the navbar `sticky` (it already is in lesson 14 — now explain in a comment
    why `sticky` was chosen over `fixed`).
26. Create a card with a "SALE" badge `absolute`-positioned at its top-right corner.

## 11 — Responsive
27. Take the landing page from lesson 14 and add one more breakpoint
    at 1024px where the features grid shows 2 columns.
28. Replace a fixed `font-size: 32px` heading with `clamp()` — test at 3 window widths.
29. Open lesson 11 on your phone (or devtools device mode). Fix anything that overflows.

## 12 — Animations
30. Add a hover effect to the profile card button: lift + shadow (0.25s ease).
31. Build a loading spinner with `@keyframes spin` (border trick from the lesson).
32. Animate the landing page hero heading sliding in on page load.

## Final projects (no peeking!)
33. Rebuild the profile card (lesson 13) from scratch without looking.
34. Rebuild the landing page (lesson 14) from scratch — then change its
    colors, copy and layout to make it YOURS.
35. **Final boss:** design a personal portfolio page — hero, about, skills grid,
    projects, contact form, footer. Fully responsive. This is your capstone.

---

Stuck? Re-read the lesson, change ONE thing at a time, refresh.
CSS is 90% experimenting. 🎨

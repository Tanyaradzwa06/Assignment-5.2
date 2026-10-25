 Short Explanation of CSS Selectors
1. Universal Selector (*) — Applies margin: 0, padding: 0, and box-sizing: border-box to all HTML elements.

2. Element Selector (p, h1, body) — Selects HTML elements by their tag names. For example, p styles all paragraphs.

3. Class Selector (.card, .container) — Selects all elements with a particular class. The .card selector styles all three service cards.

4. ID Selector (#about, #contact) — Selects a specific element by its unique ID. The #about selector styles the About section.

5. Grouping Selector (h2, h3) — Applies the same CSS properties to multiple selectors, reducing repeated code.

6. Cascade and Specificity — Two conflicting rules are used:

p { color: red; }

.card p { color: green; }
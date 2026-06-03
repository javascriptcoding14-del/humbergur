**Hamburger Menu & Animated Hero**

A small CSS-only demo that shows a responsive hamburger menu and an animated hero image.

**Description:**
- Responsive navigation with a keyboard-focusable hamburger button for small screens (`.hamburger` + `#hamburger`).
- An animated hero image that moves using the `@keyframes orbit` animation applied to `#div2`.

**Files:**
- [index.html](index.html)
- [style.css](style.css)

**Demo / Run**

- Quick (no server): Open [index.html](index.html) in your browser.


If you use VS Code, install the Live Server extension and click "Go Live".

**How it works**

- Hamburger menu: on small screens the `.hamburger` button becomes visible. When the button receives focus the adjacent `#hamburger` menu is shown using the selector `.hamburger:focus ~ #hamburger`.
- Image animation: the hero image wrapper `#div2` has `animation: orbit 3s linear infinite`, and the `@keyframes orbit` sequence applies rotation, translation and subtle scaling to make the picture move in a circular/orbit-like path.


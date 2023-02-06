
# Accessibility

---

## Description

- A `<button>` tag does not need anything special to work. Use `<button>` when you can, but it is possible to use other elements as long as you add `role="button"` and add JavaScript to replicate the button functionality.

- Just like links, you can add `class="visuallyhidden"` with descriptive text to give more context to the button's purpose.

- If a button contains an `<img>` element, make sure to set its `alt` attribute. If it contains an icon, use `aria-label` to describe the icon instead.

- You can use `<input type="image">` to make a graphical button. It takes a `src` and `alt` attribute just like traditional images.

- Button states are important, not just button styling! If you are only toggling classes to visually manage state of your components, you are likely not appropriately conveying that state to users of assistive technologies.

## Resources

- [Building Accessible Buttons with ARIA](https://www.deque.com/blog/accessible-aria-buttons)

- [User Facing State](https://css-tricks.com/user-facing-state/)

- [Using the button role](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_button_role)

- [W3C Button Examples](https://www.w3.org/TR/wai-aria-practices-1.1/examples/button/button.html)

> Some extra info:  
> WCAG Guideline

[1.1.1 Non-text Content](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=131#text-equiv-all) - All non-text content that is presented to the user has a text alternative that serves the equivalent purpose (some exceptions). (Level A)

*Note:* If non-text content is pure decoration, is used only for visual formatting, or is not presented to users, then it does not need text alternatives.
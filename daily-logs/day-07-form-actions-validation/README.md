# Day 7: Form Actions & Validation 

**Date:** July 31, 2025

## 📝 Topics Covered Today

* **Form Submission Button (`<button type="submit">`)** : Creating the button that triggers form submission.
* **Client-Side Validation (Required, Min/Max Length)** : Implementing basic HTML5 validation attributes to guide user input.
* **Checkboxes (`<input type="checkbox">`)** : Allowing users to select multiple options from a list.
* **Radio Buttons (`<input type="radio">`)** : Allowing users to select only one option from a predefined set.

## 💡 Key Concepts & Takeaways

* **`type="submit"` button:** The standard way to submit a form. Can be `<input type="submit">` or `<button type="submit">`.
* **HTML5 Validation:** Attributes like `required`, `minlength`, `maxlength` provide built-in browser-level validation without needing JavaScript.
* **`required` attribute:** Makes an input field mandatory.
* **`minlength`/`maxlength`:** Sets character limits for text inputs.
* **Checkboxes for multiple choice:** Each checkbox has a unique `id` and `name` (unless grouped for common data).
* **Radio buttons for single choice:** All radio buttons in a group **must** share the same `name` attribute to ensure only one can be selected. Each has a unique `id` and `value`.

## 💻 Daily Exercises & Code Examples

Here are the small, isolated practice files created today:

* **[Form Validation Demo](./exercises/form-validation-demo.html)**: Practice with `required` and `minlength`.
* **[Checkboxes and Radios](./exercises/checkboxes-radios-demo.html)**: Demonstrating multiple and single choice inputs.

## 🏗️ Portfolio Project Progress

Today, I completed the essential interactive features of my contact form by adding submission and validation controls.

* Added a `<button type="submit">` to my contact form in `contact.html`.
* Applied `required` to "Your Name", "Your Email", and "Your Message".
* Set a `minlength="10"` for "Your Message".
* Included "Preferred Contact Method" radio buttons (Email, Phone) and a "Subscribe to Newsletter" checkbox.

**[View Today's Portfolio Project File (contact.html)](../../project/contact.html)**

---

## 🤔 Daily Reflection

It's impressive how much functionality HTML alone can provide for forms, especially with client-side validation! Adding checkboxes and radio buttons gives users more granular control over their input. The difference between `name` attributes for radio buttons versus checkboxes was a key learning point. My form feels much more complete now!

**Challenges/Questions:**
* _How to make the contact form be functional i.e. send email?_

**Next Steps:**
* Focus on understanding HTML layout fundamentals.
* Prepare for Day 8, which covers `div` and `span`.

---

**[< Back to Main Log README](../../README.md)**
# Assignment #4: Forms and Validation

**Student:** Rayazov Mustafa  
**Group:** SE-2529  
**Live Demo (GitHub Pages):** [Visit site](https://mrreikol.github.io/WEB-Assignment-4/)

---

## Project Overview
The goal of this assignment is to understand how to create user-friendly HTML forms, apply built-in HTML5 validation, and style form components using Bootstrap 5.3 and responsive grid layout.

The project is built entirely with pure HTML5 and CSS3. It features a clean light-gray and white theme with blue accents, the Aptos Mono font, and a top navigation bar linking all tasks across separate pages.

---

## Project Structure

- `index.html` — Part 1. Basic HTML Forms
  - **Task 0 (Simple Contact Form):** Basic contact form with Name, Email, Message (`<textarea>`), and Submit button, all bound with proper `<label>` tags.
  - **Task 1 (Form with HTML5 Validation):** Form enforcing browser validation using `required`, `type="email"`, `minlength`, and `maxlength` attributes.

- `part2.html` — Part 2. Bootstrap Forms
  - **Task 2 (Bootstrap Form Styling):** Contact form styled with Bootstrap form classes (`.form-control`, `.form-label`), arranged neatly via the Bootstrap Grid system, with placeholders and helper text (`.form-text`).
  - **Task 3 (Bootstrap Validation Styles):** Demonstrates Bootstrap validation feedback classes (`.is-valid`, `.is-invalid`) with corresponding `.valid-feedback` and `.invalid-feedback` messages below each field.

- `part3.html` — Part 3. Advanced Form Project
  - **Task 4 (Registration Form):** Responsive registration form styled with Bootstrap Grid and validated using built-in HTML5 constraints and CSS validation feedback.
    - Fields: First Name, Last Name, Email Address, Password, Confirm Password
    - Options: Gender (radio buttons), Hobbies (checkboxes), Country (select dropdown)
    - Actions: Submit and Reset buttons

- `style.css` — Custom Stylesheet
  - Clean light-gray and white color scheme (`#f1f5f9`, `#ffffff`), electric blue accents (`#2563eb`), and Aptos Mono typography.

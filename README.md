# Kudakwashe Edlight Sengweni - Mini Portfolio

A personal, semantic HTML5 single-page profile and mini-portfolio webpage built for CIS2103 Web Technologies Practical Assignment 1.

## Accessibility Review & Fix 

During Thursday's peer review session, two main usability issues were identified in my initial layout:

* **Poor Colour Contrast:** The text in my headers and main sections lacked adequate contrast against the background, making it difficult to read for users with visual impairments.
* **Disappearing Placeholders:** The form inputs relied strictly on `placeholder` attributes instead of explicit `<label>` elements. Once a user clicked into a field or started typing, the hint text disappeared, leaving them without context for what the input required.

### Applied Fixes
* **Contrast Adjustment:** Updated the CSS palette to use high-contrast colour pairs that meet WCAG AA standards.
* **Explicit Labels:** Added explicit `<label>` tags linked to each input via matching `for` and `id` attributes so field titles remain permanently visible and accessible to screen readers.

---

## Prompt Log

### 1. Structured Prompt
* **Context:** I am a 2nd-year Software Engineering undergraduate student at Africa University creating an About Me bio section for my Web Technologies portfolio site.
* **Goal:** Generate a professional bio paragraph detailing my academic background and interests.
* **Constraints:** Keep it under 80 words, avoid overly grandiose phrasing, and focus on practical engineering skills.
* **Format:** Single short paragraph.

### 2. AI Raw Output
> "I am a high-achieving second-year software engineering prodigy at Africa University. I possess mastery over desktop development in C#, mobile UI design with Flutter, and backend integration using SQL Server. Driven by an unrelenting passion for perfection, I continuously architect revolutionary digital applications."

### 3. Final Edited Version
> “I am a second-year Software Engineering student at Africa University with a passion for experimenting and learning new skills. I'm currently dabbling in web development and mobile app development.”

### 4. Reflection
I edited the raw output because it used excessive self-praise that does not accurately reflect my capabilities, personality or actual current stage of learning. I altered the technical claims to accurately showcase my focus on mobile, desktop, and web development as an undergraduate student.

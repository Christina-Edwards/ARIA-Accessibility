# ARIA-Accessibility

This project demonstrates how to use ARIA (Accessible Rich Internet Applications) tags to improve web accessibility. It was created for the CodeX July2025-Lv2 course assignment.

## 🌐 Purpose

ARIA tags help users with disabilities—especially those using screen readers—understand and navigate web content more effectively. This page includes semantic HTML and ARIA attributes to enhance clarity and usability.

## 📄 Features

- Headings (`<h1>`, `<h2>`) for clear structure
- Paragraphs explaining ARIA’s purpose
- Navigation section with `role="navigation"`
- Input field with `aria-label`
- Input field with associated `<label>`
- Button with `aria-label`
- Link with `role="button"`
- Inline comments explaining each ARIA tag

## 🧪 Accessibility Testing

### Tools Used
- **Screen Reader**: macOS VoiceOver / Windows Narrator
- **Browser DevTools**: Chrome Accessibility Tree
- **Online Validator**: [WAVE Web Accessibility Tool](https://wave.webaim.org/)

### Observations
- Screen reader correctly announced the purpose of each input and button.
- Navigation role helped identify page sections.
- ARIA labels improved clarity for unlabeled elements.

### Adjustments Made
- Added `aria-label` to clarify button purpose.
- Ensured all interactive elements had accessible names.

## 🚀 Deployment

Live site: [Your GitHub Pages URL]  
Pull Request: [Link to PR from `main` to `dev`]


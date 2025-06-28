
# 🧭 Satoshium Style Guide

This style guide outlines formatting, naming conventions, and markdown practices for all documentation within the Satoshium project. It ensures consistency, clarity, and accessibility across all repositories.

---

## 📁 Folder and File Naming

- Use **lowercase** letters.
- Separate words with **hyphens** (`-`), not underscores (`_`) or camelCase.
- Examples:
  - `readme.md`
  - `glossary.md`
  - `code-of-conduct.md`

---

## 📄 Markdown Structure

- Always start with a top-level heading (`# Title`) that clearly reflects the document purpose.
- Use emoji headers for readability and categorization.
- Include a summary at the end whenever appropriate.

---

## 📝 File Format Guidelines

- All files should end in `.md` unless otherwise noted.
- Use UTF-8 encoding.
- Keep line width to approximately 80–100 characters for easier reading.

---

## 🔠 Heading Hierarchy

Use consistent heading levels:

```markdown
# Top Level Title
## Section Title
### Subsection Title
```

Avoid skipping levels or using nonstandard formats.

---

## 🔗 Links and References

- Use absolute links for cross-repository references when needed.
- Keep inline links readable and clean:
  ```markdown
  [Satoshium Core](https://github.com/satoshiumai/satoshium-core)
  ```

---

## 📌 Metadata and Notices

- Include YAML front-matter only if needed for parsing.
- License and disclaimer sections should go at the bottom of a file.

---

## 💬 Comments in Markdown

Use the standard HTML-style comments for internal notes (they won’t display in render):

```html
<!-- TODO: Expand on glossary terms -->
```

---

## 🧪 Document Testing and Validation

- Validate formatting with markdown linters (optional).
- Spellcheck using extensions or integrated tools when available.
- Ensure links are not broken.

---

## 🧾 Summary

The **Satoshium Style Guide** is a foundational reference to maintain documentation quality.  
Adhering to these practices ensures contributors, readers, and automation tools can interpret and process Satoshium documentation consistently across time and teams.

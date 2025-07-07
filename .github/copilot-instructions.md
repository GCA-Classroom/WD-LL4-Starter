# 🧑‍🍳 Copilot Instructions for Responsive Web Design (TasteBuds Lab)

## 💡 Project Context
Students are beginners learning **HTML and CSS** with a focus on **responsive web design** using Flexbox and media queries.

They are working inside GitHub Codespaces and using OpenAI’s **gpt-4o** model (unless otherwise specified). This lab simulates working for a client named “TasteBuds,” a global recipe blog.

---

## ✅ Instruction Guidelines for Copilot or ChatGPT Prompts

### 🛠️ HTML & CSS Only
- Do **not** generate or suggest JavaScript for this project.
- Focus only on **HTML** (structure) and **CSS** (styling & layout).

### 💬 Comments & Clarity
- Include **clear, beginner-friendly comments** explaining:
  - Flexbox properties like `flex-wrap`, `justify-content`, etc.
  - Media query logic and breakpoints
- Explain **why** a change helps responsiveness (e.g., “this helps the layout stack on small screens”).

### 🧱 Layout Tips
- Use **Flexbox** with simple, readable properties.
- Add `flex-wrap: wrap` where needed.
- Use **percentage widths** or `max-width` values when possible for cards.

### 📱 Media Queries
- Use `@media (max-width: 768px)` and `@media (max-width: 480px)` as breakpoints.
- Show students how to:
  - Stack cards vertically on small screens
  - Adjust spacing or text alignment
  - Improve navigation or image layout

### 🧪 Testing & Debugging
- Remind students to **use browser DevTools** (device toolbar) to preview changes.
- Include tips like “Resize the screen to see the media query in action.”

### 🙅‍♀️ What *Not* to Do
- ❌ Do **not** use frameworks (like Bootstrap or Tailwind).
- ❌ Do **not** suggest `grid` unless asked — Flexbox only.
- ❌ Do **not** use variables, mixins, or preprocessors.
- ❌ Do **not** introduce JavaScript, Node, or NPM.

---

## 🧠 AI Prompt Examples

These are the types of prompts students may ask — write answers that follow the above guidelines:

- “Why is my flexbox layout overflowing on mobile?”
- “Write a media query to stack my cards vertically”
- “How do I center items inside a flex container?”
- “What’s the best width to use for recipe cards on tablets?”
- “How do I debug CSS breakpoints in the browser?”

---


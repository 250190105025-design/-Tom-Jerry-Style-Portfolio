# 🐭 Contributing to Jerry.dev Portfolio

First off — thanks for taking the time to contribute! Every improvement makes Jerry a little faster and Tom a little more frustrated. 🧀

---

## 🤝 Code of Conduct

Be kind, be constructive, be like Jerry — clever and friendly, not like Tom.

---

## 🚀 How to Contribute

### Reporting Bugs
Use the **Bug Report** issue template. Include:
- Browser & OS details
- Steps to reproduce
- Screenshot if possible

### Suggesting Features
Use the **Feature Request** issue template. Be as descriptive as possible.

### Submitting Code

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/jerry-portfolio.git
   cd jerry-portfolio
   ```
3. **Create a branch** with a descriptive name:
   ```bash
   git checkout -b feature/add-dark-mode
   # or
   git checkout -b fix/cursor-lag-on-safari
   ```
4. **Make your changes** to `index.html`
5. **Test** in multiple browsers (Chrome, Firefox, Safari)
6. **Commit** with a clear message:
   ```bash
   git commit -m "feat: add dark mode toggle 🌙"
   # or
   git commit -m "fix: resolve cursor jitter on Safari 🐛"
   ```
7. **Push** and open a Pull Request

---

## 📐 Coding Style

Since this is a single-file project, keep it clean:

- Keep all code in `index.html` (styles in `<style>`, scripts in `<script>`)
- Use CSS variables (defined in `:root`) for all colors
- Follow the existing naming conventions:
  - CSS classes: `kebab-case`
  - JS functions: `camelCase`
  - JS constants: `camelCase`
- Comment complex animation or interaction logic
- Test on mobile — it must be responsive!
- No external libraries or CDN dependencies

---

## 🧪 Testing Checklist

Before submitting a PR, please verify:

- [ ] Opens correctly in Chrome, Firefox, and Safari
- [ ] Responsive on mobile (375px wide minimum)
- [ ] All interactive elements still work (cursor, game, bangs, confetti)
- [ ] No console errors
- [ ] Scroll animations still trigger correctly
- [ ] Nav active state still updates on scroll
- [ ] Mini-game still playable
- [ ] Konami code still works ↑↑↓↓←→←→BA

---

## 💬 Commit Message Convention

```
type: short description (emoji optional but encouraged 🐭)

Types:
  feat     — New feature
  fix      — Bug fix
  style    — CSS / visual changes only
  refactor — Code restructure, no behavior change
  docs     — README or comment updates
  chore    — Config, workflow, or repo maintenance
```

---

Thank you for contributing! 🧀 Jerry appreciates it. Tom does not.

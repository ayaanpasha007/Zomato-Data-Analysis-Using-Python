# 🤝 Contributing to Zomato Data Analysis

Thank you for your interest in contributing! Contributions of all kinds are welcome — bug fixes, new analyses, improved visualizations, or documentation updates.

---

## 📋 How to Contribute

### 1. Fork & Clone

```bash
# Fork the repo on GitHub, then:
git clone https://github.com/your-username/Zomato-Data-Analysis-Using-Python.git
cd Zomato-Data-Analysis-Using-Python
```

### 2. Create a Branch

Use a descriptive branch name:

```bash
git checkout -b feature/add-cost-analysis
# or
git checkout -b fix/notebook-path-error
```

### 3. Set Up Your Environment

```bash
python -m venv venv
source venv/bin/activate       # macOS/Linux
# venv\Scripts\activate        # Windows

pip install -r requirements.txt
```

### 4. Make Your Changes

- Keep notebook cells clean and well-commented.
- Add markdown cells to explain any new analysis sections.
- Export any new output charts to `Zomato-Output-Images/`.

### 5. Commit Your Changes

```bash
git add .
git commit -m "feat: add restaurant type vs cost heatmap"
```

Follow the commit message convention:
| Prefix | When to use |
|--------|-------------|
| `feat:` | New feature or analysis |
| `fix:` | Bug fix |
| `docs:` | Documentation update |
| `refactor:` | Code cleanup, no behavior change |
| `chore:` | Config, tooling, or dependency update |

### 6. Push & Open a Pull Request

```bash
git push origin feature/add-cost-analysis
```

Then open a Pull Request on GitHub with a clear description of your changes.

---

## ✅ Contribution Guidelines

- Do not commit large binary files or raw datasets unless absolutely necessary.
- Test your notebook from top to bottom before submitting (`Kernel > Restart & Run All`).
- Keep visualizations consistent with the existing Seaborn/Matplotlib style.
- Update `README.md` if you add new analyses or output images.

---

## 🐛 Reporting Issues

If you find a bug or have a suggestion, please [open an issue](https://github.com/your-username/Zomato-Data-Analysis-Using-Python/issues) with:

- A clear title
- Steps to reproduce (if a bug)
- Expected vs actual behavior
- Python version and OS

---

We appreciate every contribution, big or small. Thank you! 🙏

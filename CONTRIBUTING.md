# Contributing to Stella's Pine Script Starter Kit

Thanks for your interest in contributing! 🎉

## Ways to Contribute

### 🐛 Report Bugs
- Open an issue with the bug label
- Include: Pine Script version, TradingView chart, expected vs actual behavior

### 💡 Suggest Features
- Open an issue with the enhancement label
- Describe the use case and expected behavior

### 📝 Add Templates
- Create a new `.pine` file in `strategies/` or `indicators/`
- Include both English and Japanese comments
- Add description to README.md

## Template Guidelines

### Code Style
```pine
// Header with description in both languages
// 【English】...
// 【日本語】...

// Inputs section with bilingual labels
length = input.int(14, "Length / 期間")

// Clear comments explaining logic
```

### Required Elements
- [ ] MIT license header
- [ ] Bilingual comments (EN/JP)
- [ ] Input parameters with sensible defaults
- [ ] Position size 10% (avoid margin calls)
- [ ] Stop loss option

## Pull Request Process

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-template`
3. Make changes
4. Update README if adding new templates
5. Submit PR with description

## Questions?

Open an issue or reach out on X: [@StellaEntry](https://x.com/StellaEntry)

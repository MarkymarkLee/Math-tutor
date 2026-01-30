# 數學家教 | Math Tutor

互動式國中數學練習平台 - An interactive math practice platform for junior high school students.

## 📚 Available Tests

- **二元一次方程式與圖形** - Linear equations in two variables and their graphs (61 questions)

## 🚀 Getting Started

Simply open `index.html` in your browser or visit the live site at:

**https://MarkymarkLee.github.io/Math-tutor**

## 🌐 Automatic Deployment

This repository is configured with GitHub Pages. Every time you push to the `main` branch, the site will automatically deploy to GitHub Pages.

### First-time Setup

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment", select **GitHub Actions** as the source
4. Push any change to the `main` branch to trigger the first deployment

## 📁 Project Structure

```
Math-tutor/
├── index.html              # Main navigation page
├── math-tests/             # Test HTML files
│   └── 二元一次方程式與圖形.html
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions deployment workflow
└── README.md
```

## ➕ Adding New Tests

To add a new test:

1. Create your test HTML file in the `math-tests/` folder
2. Edit `index.html` and add an entry to the `tests` array in the JavaScript section:

```javascript
const tests = [
    // ... existing tests
    {
        file: "math-tests/your-new-test.html",
        title: "Test Title",
        description: "Description of the test",
        questionCount: 30,
        difficulty: "簡單", // 簡單/中等/困難
        icon: "equation", // graph, equation, geometry, or default
    },
];
```

3. Push to GitHub and it will automatically deploy!

## 🎨 Design

This project uses a modern, education-focused design with:

- **Colors**: Indigo primary (#4F46E5) with green CTA (#22C55E)
- **Typography**: Baloo 2 (headings) + Noto Sans TC (Chinese text)
- **Features**: Responsive layout, micro-interactions, and accessibility support

---

Made with ❤️ for learning mathematics

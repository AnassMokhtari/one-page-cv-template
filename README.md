# One-Page CV Template

Compact one-page A4 CV/Resume LaTeX templates (English + French), optimized for dense content and clean layout.

## 📁 Repository Structure

```
one-page-cv-template/
├─ templates/
│  ├─ en/
│  │  ├─ cv_template_en.tex      # English CV template
│  │  └─ output_cv_en.pdf        # (optional) Compiled English CV
│  └─ fr/
│     ├─ cv_template_fr.tex      # French CV template
│     └─ output_cv_fr.pdf        # (optional) Compiled French CV
├─ screenshots/
│  ├─ preview_en.png             # (optional) English CV preview
│  └─ preview_fr.png             # (optional) French CV preview
├─ README.md
├─ LICENSE
└─ .gitignore
```

## 🚀 Getting Started

### Prerequisites

You need a LaTeX distribution installed on your system:
- **Windows**: [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)
- **macOS**: [MacTeX](https://www.tug.org/mactex/)
- **Linux**: TeX Live (usually available via package manager)

Required LaTeX packages:
- inputenc
- fontenc
- babel
- geometry
- hyperref
- enumitem
- titlesec
- xcolor
- fontawesome

### Compilation

#### Using pdflatex (command line)

For English template:
```bash
cd templates/en
pdflatex cv_template_en.tex
```

For French template:
```bash
cd templates/fr
pdflatex cv_template_fr.tex
```

#### Using an IDE

You can also use LaTeX editors like:
- [TeXstudio](https://www.texstudio.org/)
- [Overleaf](https://www.overleaf.com/) (online)
- [TeXmaker](https://www.xm1math.net/texmaker/)

Simply open the `.tex` file and click the compile button.

## ✏️ Customization

### Personal Information

Edit the header section in the template:
```latex
{\Huge\bfseries Your Name}\\[8pt]
\faEnvelope\ \href{mailto:your.email@example.com}{your.email@example.com} \quad
\faPhone\ +1 234 567 8900 \quad
```

### Sections

The templates include the following sections:
- **Professional Summary**: Brief overview of your experience
- **Work Experience**: Detailed work history
- **Education**: Academic background
- **Technical Skills**: Programming languages, tools, frameworks
- **Selected Projects**: (Optional) Showcase your projects
- **Certifications**: (Optional) Professional certifications

Feel free to add, remove, or reorder sections according to your needs.

### Styling

You can customize colors, fonts, and spacing:
```latex
% Change section color
\titleformat{\section}
{\large\bfseries\color{blue!60!black}}  % Change color here
```

## 📝 Features

- ✅ **One-page layout**: Optimized to fit all content on a single A4 page
- ✅ **Clean design**: Professional and modern appearance
- ✅ **Bilingual**: Both English and French versions included
- ✅ **Easy customization**: Well-commented and structured code
- ✅ **Hyperlinks**: Clickable email, LinkedIn, and GitHub links
- ✅ **Icon support**: FontAwesome icons for contact information

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 💡 Tips

1. **Keep it concise**: One page forces you to include only the most relevant information
2. **Use action verbs**: Start bullet points with strong action verbs
3. **Quantify achievements**: Include numbers and percentages where possible
4. **Tailor your CV**: Customize for each job application
5. **Proofread**: Check for typos and grammatical errors

## 🔗 Resources

- [LaTeX Documentation](https://www.latex-project.org/help/documentation/)
- [Overleaf Templates](https://www.overleaf.com/latex/templates)
- [FontAwesome Icons](https://fontawesome.com/v4.7.0/icons/)

---

**Happy job hunting! 🎯**

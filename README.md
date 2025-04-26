# wesleystoryiii-singularity-scope
The Singularity Scope – A blog exploring AI, machine learning, and humanity’s path toward the technological singularity. Powered by Staticman comments and Prism.js.
# 🧠 The Singularity Scope

**The Singularity Scope** is a technical blog created by [Wesley Story III](https://www.wesleystoryiii.com) that explores cutting-edge developments in artificial intelligence, machine learning, large language models, and humanity’s journey toward the singularity.

This repository powers the blog’s content, including post metadata, Staticman comment submissions, and configuration files for community contributions and site features.

---

## 🚀 Live Site

👉 [Visit The Blog](https://www.wesleystoryiii.com/singularity-scope)

---

## ✨ Features

- ⚡ **Hand-coded HTML5 blog** for speed, SEO, and full control
- 💬 **Staticman-powered commenting system** (YAML-based pull request model)
- 🎨 **Prism.js integration** for clean code syntax highlighting
- 🔍 **Client-side JavaScript search**
- 📰 **RSS feed** support for syndication
- 🔐 Built with **accessibility** and **responsive design** in mind

---

## 📂 Repo Structure

```
├── staticman.yml           # Staticman configuration
├── data/
│   └── comments/           # Auto-generated comment files by post slug
├── posts/                  # Blog posts (e.g., .md or .html)
├── css/                    # Custom styles
└── index.html              # Blog homepage layout
```

---

## 🛠 Staticman Setup

This repo uses the hosted Staticman instance (`https://staticman3.herokuapp.com`).

To submit a comment:
- A form submission sends a POST request to Staticman
- A pull request is created in `/data/comments/[slug]/`
- Once approved/merged, the comment is visible

👉 See `staticman.yml` for detailed config.

> Want to use Staticman on your own site? [Learn more here](https://staticman.net/docs/).

---

## 🧪 Comment Testing

1. Submit a comment via the blog.
2. Check the `Pull Requests` tab in GitHub.
3. Merge the PR to publish the comment.

---

## 📢 Contributing

Pull requests to improve posts, styling, or features are welcome.  
All feedback and collaboration are appreciated!

---

## 🧠 About the Author

Wesley Story III is a seasoned IT professional and AI integration specialist with over 20 years of experience in software development, embedded systems, and AI/LLM technologies.

Connect:
- 🌐 [Personal Website](https://www.wesleystoryiii.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/wesleystoryiii)

---

## 📄 License

MIT License — free to use, customize, and build upon.

## License

The source code of this project is licensed under the [MIT License](LICENSE).

The blog content (posts, writing) is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

Feel free to fork and reuse the code, and share the content with attribution — but please don’t sell it.


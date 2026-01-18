<p align="center">
  <img src="https://img.shields.io/github/stars/AnotherChocoMilky/ChocoX-Library?style=for-the-badge" alt="GitHub stars" />
  <img src="https://img.shields.io/github/forks/AnotherChocoMilky/ChocoX-Library?style=for-the-badge" alt="GitHub forks" />
  <img src="https://img.shields.io/github/issues-pr/AnotherChocoMilky/ChocoX-Library?style=for-the-badge" alt="Open pull requests" />
</p>

<p align="center">
  <img src="static/icons/logo1024x1024.png" alt="ChocoX Library logo" width="200" />
</p>

<h1 align="center">ChocoX Library</h1>

<p align="center">
  A lightweight static web app for browsing and downloading IPAs from your favorite repositories.<br />
  Easy to self-host, easy to customize, and simple to extend with more repos.
</p>

<p align="center">
  <strong>Live:</strong> <a href="https://choco-x.vercel.app">https://choco-x.vercel.app</a>
</p>

---

## Features

- Static HTML web app
- Minimal and lightweight
- Import personal repositories

---

## Contributing (adding repos)

Want to add a repo to the library? Thanks.

1. Fork this repository
2. Add your repo to the repos JSON file (see example below)
3. Commit your changes
4. Open a pull request

### Example

Add an entry like this to the repos JSON file:

```json
{
  "url": "https://example.com/repo.json"
}
```


---

## Self-hosting / Getting started

### Clone the repository

```bash
git clone https://github.com/AnotherChocoMilky/ChocoX-Library.git
cd ChocoX-Library
```

### Run locally

You can open `index.html` directly in your browser, but using a local server is recommended:

```bash
npx http-server .
```

---

## Background

This project is based on **chocomilkyX** by **@gablili**, which itself was a fork of **my** original project.  
**ChocoX Library** refreshes the UI, added repos, improves customization, and continues development while maintaining compatibility with existing repo formats.

> [!WARNING]
> **ChocoX does not host any IPA files.**
> All downloadable files are provided by third-party repositories.
> You are responsible for complying with the terms and conditions of the original sources.

---

## License

Licensed under the **GPL-3.0**. See the `LICENSE` file for details.

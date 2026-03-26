# Git It Done

Search any GitHub user's repositories and browse their open issues — powered by the GitHub REST API.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![GitHub API](https://img.shields.io/badge/GitHub_API-181717?style=flat&logo=github&logoColor=white)

---

## About

Git It Done is a client-side web app that lets you search for GitHub users, view their public repositories, and drill into open issues for any repo. It demonstrates working with third-party REST APIs, dynamic DOM manipulation, and multi-page navigation — all without a framework.

## Features

- Search GitHub users by username
- Browse public repositories with language filters
- View open issues for any selected repository
- Dynamic page transitions between search and detail views
- Fetch API with error handling and loading states

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript (ES6+) |
| Data | GitHub REST API v3 |
| HTTP | Fetch API |

## Getting Started

```bash
git clone https://github.com/coleyrockin/git-it-done.git
cd git-it-done
```

Open `index.html` in your browser to start searching.

## Project Structure

```
├── assets/
│   ├── css/        # Stylesheets
│   └── js/         # Application logic & API calls
├── index.html          # Search page
└── single-repo.html    # Issue detail page
```

---

Built by [Boyd Roberts](https://github.com/coleyrockin)

# 🧠 Memolify — Markdown Knowledge Base

**Memolify** is a fast, minimalistic knowledge base platform built for teams and individuals who prefer writing in Markdown. It turns simple `.md` files into a searchable, responsive documentation site — instantly.

You can try it out live at 👉 [https://memolify.app](https://memolify.app)  
_No signup required. Just search, browse, and explore._

---

## ✨ What Is It?

Memolify helps you organize and access Markdown-based documentation through a clean, modern web interface. It's powered by a full-text search engine and optimized for fast content discovery.

Whether you're managing developer guides, internal wikis, product specs, or personal notes — Memolify makes it painless.

---

## 🚀 Features

- 🧭 **Instant full-text search** — Powered by Apache Lucene
- 📄 **Markdown rendering** — With support for headings, code blocks, links, and more
- 🧱 **Clean, responsive UI** — Built with React + Next.js
- 🔌 **RESTful API** — Access your content programmatically
- 🔍 **Keyword ranking** — Smart relevance scoring in search
- 🔐 **Private content storage** — Markdown files are stored securely and versioned via Git

---

## 🌐 Try It Now

The live version is hosted at:

🔗 [https://memolify.app](https://memolify.app)

You can explore real examples and test search capabilities right in your browser.  
We recommend bookmarking it if you frequently access Markdown docs.

---

## 🧰 Technology Stack

| Layer        | Technology                                                                 |
| ------------ | --------------------------------------------------------------------------- |
| **Frontend** | React + Next.js + `react-markdown`                                          |
| **Backend**  | Java 17 + Spring Boot 3                                                     |
| **Search**   | Apache Lucene (in-memory full‑text indexing)                                |
| **Storage**  | Git-tracked Markdown files (with potential for S3 or headless CMS later)    |

---

## 📖 API Overview

The backend provides a versioned REST API (`/api/v1`) that powers the frontend and can be integrated with external tools.

Key endpoints include:

| Method     | Endpoint            | Purpose                                      |
| ---------- | ------------------- | -------------------------------------------- |
| `GET`      | `/contents`         | List all documents (filterable by tags, title) |
| `GET`      | `/contents/{title}` | Retrieve a specific Markdown document        |
| `POST`     | `/contents/search`  | Perform a full-text search query             |

> The full API spec is available upon request.

---

## 📝 License

Memolify is a closed-source product.  
If you're interested in enterprise use, custom integrations, or self-hosted options, please contact us.

---

## 💬 Feedback

We’d love to hear from you!  
Questions, suggestions, or feature requests? Reach out via the contact form at [memolify.app](https://memolify.app).


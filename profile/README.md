<div align="center">
  
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./logo-light.svg">
    <img src="./logo-dark.svg" width="450" alt="Crawlee Cloud Logo" />
  </picture>

  **Your Scrapers, Your Cloud ✨**

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/crawlee-cloud/crawlee-cloud/blob/main/LICENSE)

</div>

---

### 🚀 What is Crawlee Cloud?

Crawlee Cloud is a self-hosted platform that lets you run **Crawlee and Apify Actors** on your own infrastructure. We provide an open-source implementation of the Apify API, meaning you can point the official [Apify SDK](https://sdk.apify.com) at your own servers and everything just works.

- **🏠 Your Infrastructure:** Deploy on your own servers, cloud, or anywhere you like.
- **🔒 Complete Privacy:** Your data stays exactly where you want it.
- **⚡ SDK Compatible:** Works with your existing Actors without code changes.

### 🛠️ Core Project

| Project | Description |
| :--- | :--- |
| **[crawlee-cloud](https://github.com/crawlee-cloud/crawlee-cloud)** | The monorepo containing the API Server, Runner, CLI, and Dashboard. |

### 🌟 Getting Started

1. **Deploy the platform:**
   ```bash
   git clone https://github.com/crawlee-cloud/crawlee-cloud.git
   docker compose up -d
   ```

2. **Point your scraper:**
   ```bash
   export APIFY_API_BASE_URL="http://localhost:3000/v2"
   node main.js
   ```

### 📚 Resources

- [📖 Documentation](https://crawlee.cloud/docs)
- [�️ Roadmap](https://github.com/crawlee-cloud/crawlee-cloud/blob/main/ROADMAP.md)
- [� Report a Bug](https://github.com/crawlee-cloud/crawlee-cloud/issues)
- [� Discussions](https://github.com/crawlee-cloud/crawlee-cloud/discussions)

---

<div align="center">
  <sub>Built with ❤️ for the web scraping community</sub>
</div>
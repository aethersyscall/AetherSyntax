<div align=center>
    
# AetherSyntax

**A zero-dependency, static cheatsheet library for modern developers.**


![AetherSyntax Banner](https://img.shields.io/badge/Aether-Syntax-9580FF?style=for-the-badge&labelColor=13111B)
![Engine](https://img.shields.io/badge/Engine-Stable_v1.0.0-80FFEA?style=for-the-badge&labelColor=13111B)
![License](https://img.shields.io/badge/License-MIT-FF70B8?style=for-the-badge&labelColor=13111B)

**AetherSyntax** is a lightweight documentation hub designed for speed and readability. It provides instant access to syntax guides for languages like Rust, C++, and JavaScript without the bloat of heavy frameworks.
</div>

---

## ⚡ Key Features

*   **Zero Build Step:** No Webpack, React, or Node.js required. Runs natively in the browser.
*   **JSON-Driven:** The dashboard is generated dynamically from a simple `cheatsheets.json` manifest.
*   **Instant Search:** Real-time filtering by title and tags.
*   **Dual Environment:** Built-in Dark (Eclipse) and Light (Bliss) modes with state persistence.
*   **Mobile First:** Responsive grid layout that adapts to any device.

---

## 🚀 Usage

### Option 1:

Visit the live github page [here](aethersyscall.github.io/AetherSyntax)

### Option 2:

Since this is a static site, you only need a web server to run it (to handle JSON fetching via CORS).

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AetherSyscall/AetherSyntax.git
    cd AetherSyntax
    ```

2.  **Run locally:**
    ```bash
    # Using Python 3
    python3 -m http.server 8000
    
    # Or using Node
    npx serve .
    ```

3.  **Open:** Navigate to `http://localhost:8000` in your browser.

---
## How to Contribute?

Visit [CONTRIBUTING.md](./CONTRIBUTING.md)

## 📜 License

Distributed under the Apache 2.0 License.

<div align=center>

# AetherSyntax

 **Psychological Syntax Highlighting.**  
 A cognitive documentation library engineered for flow state.

[![License](https://img.shields.io/badge/License-Apache_2.0-9580FF?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/System-Nominal-FF70B8?style=for-the-badge)](https://aethersyscall.github.io/AetherSyntax)
[![Theme](https://img.shields.io/badge/Theme-Aether_Amethyst-80FFEA?style=for-the-badge)](https://github.com/AetherSyscall/AetherAmethyst)

[Live here ](https://aethersyscall.github.io/AetherSyntax)

</div>

---

## 🏗 Architecture

AetherSyntax is a **Distributed Static System**. It does not rely on a backend database.

### 1. The Dashboard (`index.html`)
The entry point. It acts as a registry to generate a searchable constellation of knowledge fragments.

### 2. The Fragments (`/cheatsheets/*.html`)
Each cheatsheet is a **Self-Contained Polyglot**.
*   **Zero Dependencies:** Each HTML file contains its own CSS, JS, and Theme Engine.
*   **Portable:** You can email a single `.html` file to a colleague, and it will retain its theming, interactivity, and toggle states perfectly offline.

### 3. The Generator (`AetherMarkdown`)
I do not write HTML manually. I use the [AetherMarkdown Engine](https://aethersyscall.github.io/AetherFragments/fragments/AetherMarkdown.html) to transpile Markdown into the Aether HTML bundle.

---

## 🚀 Quick Start

### Running Locally
Because this is a vanilla stack, you only need a basic HTTP server.

```bash
# Clone the constellation
git clone https://github.com/your-username/AetherSyntax.git
cd AetherSyntax

# Ignite (Python)
python3 -m http.server 8080

# Ignite (Node)
npx serve .
```

### The Dual Environment
The system comes equipped with two distinct psychological modes:
The theme used here: [AetherAmethyst](https://aethersyscall.github.io/AetherAmethyst)
*   **🌑 Eclipse (The Void):** Deep Indigo (`#13111B`) for high-contrast architectural focus.
*   **🌸 Bliss (The Paper):** Lavender White (`#FDF7FF`) for high-clarity review in daylight.

---

## 🛠 Workflow

To expand the library, follow the **Generator Pipeline**:

1.  **Draft:** Open `AetherMarkdown.html`.
2.  **Write:** Create your documentation using standard Markdown.
3.  **Export:** Click **"HTML"** to generate the self-contained bundle.
4.  **Deploy:** Move the file to `cheatsheets/` and register it in `cheatsheets.json`.

*See [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed rendering standards.*

---

## 📂 Project Structure

```text
AetherSyntax/
├── cheatsheets/           # The Knowledge Fragments
│   ├── rust.html          # Generated via AetherMarkdown
│   ├── cpp.html
│   └── ...
├── index.html             # The Dashboard UI
├── README.md              # You are here
└── CONTRIBUTING.md        # The Standards
```

---

&copy; 2026 AetherSyscall. Licensed under Apache 2.0.

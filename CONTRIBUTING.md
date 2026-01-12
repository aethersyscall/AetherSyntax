# 🛠 How to Add a Cheatsheet

We use a decentralized workflow. You do not write HTML manually; you write Markdown and convert it.

### Step 1: Write & Convert
1.  Go to the official converter: [AetherMarkdown Tool](https://aethersyscall.github.io/AetherFragments/fragments/AetherMarkdown.html).
2.  Write your guide in standard Markdown.
3.  Click **Convert** to generate the HTML structure.

### Step 2: Create File
1.  Create a new file in the `cheatsheets/` directory (e.g., `cheatsheets/python.html`).
2.  Paste the generated HTML into this file.
3.  **Important:** Ensure the file links back to the main styles/scripts at the top and bottom (copy the structure from `cheatsheets/rust.html` if unsure).

### Step 3: Register Module
Open `cheatsheets.json` in the root directory and add your new entry:

```json
{
  "title": "Python",
  "description": "Decorators, Generators, and AsyncIO patterns.",
  "tags": ["Scripting", "Backend"],
  "path": "./cheatsheets/python.html"
}
```

The engine will automatically detect the new file and add it to the dashboard.

---

## 📂 Project Structure

```text
AetherSyntax/
├── index.html          # Main Dashboard
├── cheatsheets.json    # Data Manifest
└── cheatsheets/        # Content Pages
    ├── rust.html
    ├── c++.html
    └── html.html
```

---

## 🎨 Customization

The look and feel is controlled via CSS Variables in `style.css`. 

To modify the color palette, edit the `:root` variables under `[data-theme="eclipse"]` (Dark) or `[data-theme="bliss"]` (Light). No recompilation is needed.

---

## 📜 License

Distributed under the Apache 2.0 License.


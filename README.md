<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:6d28d9&height=180&section=header&text=XML%20Tree%20Explorer&fontSize=38&fontColor=ffffff" width="100%" alt="XML Tree Explorer banner"></p>
<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=A78BFA&center=true&vCenter=true&width=620&lines=Explore+XML+as+a+readable+tree;Search+elements+and+inspect+paths" alt="Animated tagline"></p>
<p align="center"><img src="assets/mark.svg" width="100" alt="XML tree icon"></p>
<p align="center"><img src="https://img.shields.io/github/license/CyberLoop-dev/xml-tree-explorer?style=flat-square" alt="License"><img src="https://img.shields.io/github/languages/top/CyberLoop-dev/xml-tree-explorer?style=flat-square" alt="Language"><img src="https://img.shields.io/github/stars/CyberLoop-dev/xml-tree-explorer?style=flat-square" alt="Stars"><img src="https://img.shields.io/github/last-commit/CyberLoop-dev/xml-tree-explorer?style=flat-square" alt="Last commit"></p>

## 🧭 Overview
XML Tree Explorer turns pasted or locally selected XML into an expandable element tree. It shows attributes, short text previews, and indexed paths so large documents are easier to inspect.

## ✨ Features
- 🌳 Expand and collapse XML elements.
- 🔎 Search element names, attribute values, and text.
- 🧭 Inspect indexed paths such as `/catalog[1]/book[2]`.
- 📂 Open a local XML file or load the included sample.
- 🔒 Parsing happens in the browser; no XML is uploaded.

## 🎬 Demo
No hosted demo is published. Use **Load sample** after starting the local server.

## 🚀 Quick Start
Requires Node.js 18 or newer.
```bash
npm start
```
Open [http://localhost:4176](http://localhost:4176).

## 🧰 Tech Stack
- Node.js built-in HTTP server
- Browser DOMParser, HTML, CSS, and JavaScript
- No runtime dependencies

## 🗂️ Folder Structure
```text
xml-tree-explorer/
├── assets/mark.svg
├── public/{app.js,index.html,style.css}
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🗺️ Roadmap
- [ ] Add namespace-aware path display.
- [ ] Add a copy-path action for each node.
- [ ] Add an optional raw formatted XML view.

## 🤝 Contributing
Pull requests are welcome. Keep parsing local, render untrusted XML as text, and document browser limitations.

## 📄 License
Released under the [MIT License](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,100:111827&height=100&section=footer" width="100%" alt="Footer wave"></p>
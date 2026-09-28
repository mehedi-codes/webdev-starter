# WebDev Starter

A minimal and organized folder structure for frontend projects.

This repository is intentionally lightweight and keeps the setup flexible. It gives you a clean starting point without forcing a specific framework, build tool, or workflow.

## Why use this template?

- Clean separation between source files and generated output
- Easy to extend for small or medium frontend projects
- Suitable as a starting point for custom builds and tooling
- Keeps the project structure simple and readable

## Folder structure

```text
webdev-starter/
├─ dist/                  # Generated output files
│  ├─ assets/
│  │  ├─ favicons/
│  │  ├─ fonts/
│  │  └─ img/
│  ├─ css/
│  ├─ js/
│  ├─ pages/
│  └─ index.html
├─ src/                   # Source files
│  ├─ assets/
│  │  ├─ favicons/
│  │  ├─ fonts/
│  │  └─ img/
│  ├─ js/
│  │  └─ sctipt.js
│  ├─ pages/
│  │  ├─ about.html
│  │  └─ contact.html
│  ├─ scss/
│  │  ├─ components/
│  │  ├─ global/
│  │  ├─ layout/
│  │  ├─ util/
│  │  └─ style.scss
│  └─ index.html
├─ .gitattributes
├─ .gitignore
├─ LICENSE
├─ README.md
└─ .gitkeep placeholders if needed
```

## Getting started

```bash
git clone https://github.com/mehedi-codes/webdev-starter.git
cd webdev-starter
```

From here, you can:

- add your own HTML, CSS, and JavaScript files
- customize the folder structure for your project
- connect the starter to your preferred tooling
- build your own workflow based on Vite, Gulp, or any other setup you prefer

## Notes

This repository is a template scaffold, not a preconfigured framework starter. It does not include a full build pipeline, package manager setup, or framework-specific commands by default.

If you want a more opinionated setup, you can add your preferred tooling on top of this structure.

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](./LICENSE) file for details.

## Contributing

Contributions are welcome. If you have ideas for improving the structure, documentation, or starter conventions, feel free to open an issue or submit a pull request.

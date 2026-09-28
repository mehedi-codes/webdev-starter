![webdev-starter](https://socialify.git.ci/devbytemehedi/webdev-starter/image?description=1&font=KoHo&language=1&name=1&pattern=Solid&theme=Auto)


## Table of Contents

- [Introduction](#intro)
- [Features](#ft)
- [Folder Structure](#fst)
- [Getting Started](#gs)
  - [Prerequisites](#prt)
  - [Installation](#ins)
- [Usage](#usg)
  - [Development Mode](#dev)
  - [Build Process](#bd)
- [License](#ls)
- [Contributing](#cntrb)
- [Acknowledgements](#ack)

<h2 id="intro"> 🌟 Introduction</h2>

🚀 **WebDev Starter** : A structured boilerplate project for frontend developers ⚡️🎨. Unleash your creativity with an organized folder structure and best practices, igniting web development projects like never before! 💪💻 Start your journey now and witness the magic unfold. 🌟🔥

<h2 id="ft">✨ Features</h2>

- 🚀 Easy setup and 🔧 configuration
- 📁 Well-organized folder structure for efficient 💼 project management
- 🎨 Modular SCSS architecture using 🧩 BEM methodology
- 🤖 Automated build process with 🌊 Gulp
- 🔍 Minification and concatenation of CSS and JavaScript files
- 🖼️ Image optimization
- 🔨 HTML minification
- 🌐 Responsive design-ready
- ♻️ Live reload for development
- 📄 Suitable for single-page and 📑 multi-page websites
- 🔀 Version control (Git) and hosting 🐙 (GitHub) compatibility
- 📖 Comprehensive documentation for easy reference and usage
- 📜 Licensed under the GPL 3.0 for open-source collaboration

<h2 id="fst"> 📂 Folder Structure </h2>

Here is the folder structure of the project:

```js
webdev-starter           (Project Name)
 ┣━ dist                 (Production files)
 ┃ ┣━ assets             (Static assets)
 ┃ ┃ ┣━ favicons         (Favicon files)
 ┃ ┃ ┣━ fonts            (Fonts directory)
 ┃ ┃ ┗━ img              (Optimized images)
 ┃ ┣━ css                (Minified CSS files)
 ┃ ┣━ js                 (Minified JS files)
 ┃ ┣━ pages              (Minified HTML pages)
 ┃ ┃ ┣━ about.min.html   (Minified about page)
 ┃ ┃ ┗━ contact.min.html (Minified contact page)
 ┃ ┗━ index.html         (Minified index.html)
 ┣━ src                  (Source files)
 ┃ ┣━ assets             (Static assets)
 ┃ ┃ ┣━ favicons         (Favicon files)
 ┃ ┃ ┣━ fonts            (Fonts directory)
 ┃ ┃ ┗━ img              (Images directory)
 ┃ ┣━ js                 (JavaScript files)
 ┃ ┃ ┗━ sctipt.js        (Custom JavaScript code)
 ┃ ┣━ pages              (HTML pages)
 ┃ ┃ ┣━ about.html       (About page source)
 ┃ ┃ ┗━ contact.html     (Contact page source)
 ┃ ┣━ scss               (SCSS files)
 ┃ ┃ ┣━ components       (SCSS components)
 ┃ ┃ ┣━ global           (Global SCSS styles)
 ┃ ┃ ┣━ layout           (SCSS layout styles)
 ┃ ┃ ┣━ util             (Utility SCSS styles)
 ┃ ┃ ┗━ style.scss       (Main SCSS entry point)
 ┃ ┗━ index.html         (Main HTML file)
 ┣━ .gitattributes       (Git attributes file)
 ┣━ .gitignore           (Git ignore file)
 ┣━ gulpfile.js          (Gulp configuration file)
 ┣━ LICENSE              (License information)
 ┣━ package.json         (Package configuration file)
 ┗━ README.md            (Project documentation)
```

<!-- ## Customization -->
<div id="gs"><h2>🚀 Getting Started </h2></div>

<div id="prt"><h3>⚙️ Prerequisites </h3></div>

Before getting started with the project, make sure you have the following **prerequisites** installed on your system:

[![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://github.com/nodejs/node.git) [![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://github.com/npm/cli.git) [![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)

In this documentation we are using Windows Operating System :

[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://aka.ms/windows11)

Open Terminal or Powershell As Admin

[![Windows Terminal](https://img.shields.io/badge/windows%20terminal-4D4D4D?style=for-the-badge&logo=windows%20terminal&logoColor=white)](https://aka.ms/terminal) [![Powershell](https://img.shields.io/badge/powershell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](https://github.com/PowerShell/PowerShell.git)

This command will install the latest available versions of [NodeJS](https://nodejs.org/) and [Git](https://git-scm.com/) using [Winget](https://github.com/microsoft/winget-cli.git).

```pwsh
winget install --id OpenJS.NodeJS Git.Git
```

<details>
  <summary>Winget ?</summary>

[Winget](https://github.com/microsoft/winget-cli.git) comes with Windows by deafult, to check type `winget -v` to get installed version.

If not type this to install:

```pwsh
Set-ExecutionPolicy RemoteSigned -Scope Process -Force; iex "& { $(irm https://aka.ms/winget-cli) }"; Set-ExecutionPolicy <original_execution_policy> -Scope Process -Force
```

</details>
<div id="ins"><h3>🛠️ Installation</h3></div>

**Clone or [Download](https://github.com/devbytemehedi/webdev-starter/archive/refs/heads/main.zip) this repository :**

```bash
git clone https://github.com/devbytemehedi/webdev-starter.git
```

**Navigate to the project directory :**

```bash
cd webdev-starter
```

**Install the required dependencies :**

```bash
npm install
```

<div id="usg"><h2>📝 Usage</h2></div>

<div id="dev"><h3>🚧 Development Mode</h3></div>

During development, you can run the project in development mode with live reloading
Start the development server :

```bash
npm run dev
```

This will compile the SCSS to CSS, concatenate JavaScript files, optimize images, and launch a local development server. Any changes you make to the source files will automatically trigger a reload in the browser.

<div id="bd"><h3>🏗️ Build Process
</h3></div>

The project uses Gulp for automation. The build process includes:

- Compiling SCSS files to CSS and minifying them.
- Concatenating and minifying JavaScript files.
- Optimizing images for production.
- Minifying HTML files.
- Copying static assets to the dist directory.

To build the project for production, use the following command :

```bash
npm run build
```

This will compile and minify the SCSS and JavaScript files, optimize images, minify HTML files, and copy static assets to the `dist` directory. The final production-ready files will be available in the `dist` folder.

<div id="ls"><h2>📄 License</h2></div>

This project is licensed under the GPL 3.0 License. See the [LICENSE](./LICENSE) file for details.

<div id="cntrb"><h2>🤝 Contributing</h2></div>

Contributions are welcome! Feel free to fork this repository and submit pull requests to suggest improvements or add new features.

<div id="ack"><h2>🙏 Acknowledgements</h2></div>

- [Gulp](https://gulpjs.com/) - A popular task runner for web development.
- [Sass](https://sass-lang.com/) - A CSS preprocessor that enhances the styling workflow.
- [BEM](https://en.bem.info/) - A methodology for writing maintainable and reusable CSS.
- [Node.js](https://nodejs.org/) - A JavaScript runtime environment for building server-side and networking applications.

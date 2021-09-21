# Learn Electron

> [`Electron`](https://electronjs.org) is an open-source framework developed and maintained by GitHub. Electron allows for the development of desktop GUI applications using web technologies: It combines the Chromium rendering engine and the `Node.js` runtime.

---

## Links and Resources

* [`electron/electron`](https://github.com/electron/electron)
  * [Documentation](https://electronjs.org/docs)
  * [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start)

---

## Installation

* [Tutorial/Installation](https://electronjs.org/docs/tutorial/installation)

```bash
$ npm i -g electron        # Globally install
$ npm i -D electron@latest # Project install
# Electron   11.5.0
# Node       12.18.3
# Chromium   87.0.4280.141
```

## Application Structure

A basic `Electron` app would have the following folder structure:

```text
app/
├── package.json
├── main.js
└── index.html
```

---

## Project Structure

```md
.
├── app                  # Electron app
│   ├── package.json
│   ├── main.js
│   └── index.html
├── .editorconfig        # Editor configuration
├── .eslintrc            # Eslint configuration
├── .gitignore           # Git ignore rules
├── .np-config.json      # NPM publish (np) configuration
├── LICENSE              # Project License
├── package.json         # NPM package configuration
└── README.md            # Project README
```

---

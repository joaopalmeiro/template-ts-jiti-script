# template-ts-jiti-script

Opinionated [TypeScript](https://www.typescriptlang.org/) + [jiti](https://github.com/unjs/jiti) template for new scripts.

## Getting Started

1. Go to or create the project folder.
2. Get the template files:

```bash
npx degit github:joaopalmeiro/template-ts-jiti-script
```

or

```bash
npx degit github:joaopalmeiro/template-ts-jiti-script --force
```

3. Search for `template-ts-jiti-script` and replace it with the project name. Ignore the template repository URL in the [NOTES.md](NOTES.md) file.
4. Search for `Opinionated TypeScript + jiti template for new scripts.`/`Opinionated [TypeScript](https://www.typescriptlang.org/) + [jiti](https://github.com/unjs/jiti) template for new scripts.` and replace it with the (short) project description.
5. Search for `João Palmeiro` and replace it with the author's name.
6. Search for `joaopalmeiro@proton.me` and replace it with the author's email address.
7. Change the `author.url` field in the `package.json` file to the author's website/social media profile.
8. Install [fnm](https://github.com/Schniz/fnm) (if necessary).
9. Run the first two commands in the [`Development`](#development) section to install [Node.js](https://nodejs.org/en) and the development dependencies.
10. Open the [NOTES.md](NOTES.md) file and install the project-specific dependencies according to the first command in the [`Commands`](NOTES.md#commands) section. Run the second command if you are going to use Node.js modules.
11. Delete the [TEMPLATE.md](TEMPLATE.md) file.
12. Delete the [`Getting Started`](#getting-started) section.

## Development

Install [fnm](https://github.com/Schniz/fnm) (if necessary).

```bash
fnm install && fnm use && node --version && npm --version
```

```bash
npm install
```

```bash
npm run dev
```

```bash
npm run lint
```

```bash
npm run format
```

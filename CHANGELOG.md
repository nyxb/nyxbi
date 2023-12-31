# Changelog


## v0.0.20

[compare changes](https://github.com/nyxb/cli/compare/v0.0.19...v0.0.20)

### 💅 Refactors

- **src/utils/templates.ts:** Standardize object property separator from semicolon to comma for consistency ([4c55e26](https://github.com/nyxb/cli/commit/4c55e26))

### 🎨 Styles

- **package.json:** Add newline at end of file for POSIX compliance ([18f0141](https://github.com/nyxb/cli/commit/18f0141))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.19

[compare changes](https://github.com/nyxb/cli/compare/v0.0.18...v0.0.19)

### 🚀 Enhancements

- **commands/index.ts:** Add dynamic import for 'add' command ([cac39f4](https://github.com/nyxb/cli/commit/cac39f4))
- **commands/add.ts:** Add new command to create template files ([8e3db39](https://github.com/nyxb/cli/commit/8e3db39))
- **utils/esm.ts:** Add ESM utility functions for module resolution ([f94dd02](https://github.com/nyxb/cli/commit/f94dd02))
- **utils/kit.ts:** Add utility to load @nuxt/kit with polyfill support ([e4e8fc8](https://github.com/nyxb/cli/commit/e4e8fc8))
- **utils/templates.ts:** Add template utility functions for scaffolding ([bc0e700](https://github.com/nyxb/cli/commit/bc0e700))

### 🏡 Chore

- **release:** V0.0.18 ([ea6cb44](https://github.com/nyxb/cli/commit/ea6cb44))
- **.gitignore:** Add .env to .gitignore to prevent committing sensitive environment variables ([a75113a](https://github.com/nyxb/cli/commit/a75113a))

### 🎨 Styles

- **.vscode/settings.json:** Update auto fix settings to explicit values ([f4b3b33](https://github.com/nyxb/cli/commit/f4b3b33))
- Reformat code for consistency in various files ([37a8a77](https://github.com/nyxb/cli/commit/37a8a77))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.18

[compare changes](https://github.com/nyxb/cli/compare/v0.0.17...v0.0.18)

### 💅 Refactors

- **init.ts:** Use --quiet flag with git init command to suppress output and make logs cleaner ([f74fe70](https://github.com/nyxb/cli/commit/f74fe70))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.17

[compare changes](https://github.com/nyxb/cli/compare/v0.0.16...v0.0.17)

### 🏡 Chore

- **init.ts:** Add --quiet flag to git commit command to suppress output and make logs cleaner ([c240a6c](https://github.com/nyxb/cli/commit/c240a6c))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.16

[compare changes](https://github.com/nyxb/cli/compare/v0.0.15...v0.0.16)

### 💅 Refactors

- **init.ts:** Simplify git initialization and first commit process by combining commands into a single execaCommand call to improve code readability and maintainability ([a3402c2](https://github.com/nyxb/cli/commit/a3402c2))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.15

[compare changes](https://github.com/nyxb/cli/compare/v0.0.14...v0.0.15)

### 🚀 Enhancements

- **init.ts:** Enhance error logging by adding stdout and stderr to catch blocks for better debugging ([76d11e4](https://github.com/nyxb/cli/commit/76d11e4))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.14

[compare changes](https://github.com/nyxb/cli/compare/v0.0.13...v0.0.14)

### 💅 Refactors

- **init.ts): replace process.chdir with git --git-dir and --work-tree options to avoid changing the current working directory 🐛 fix(init.ts:** Prevent potential issues with other operations that depend on the current working directory ([f54a478](https://github.com/nyxb/cli/commit/f54a478))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.13

[compare changes](https://github.com/nyxb/cli/compare/v0.0.12...v0.0.13)

### 🚀 Enhancements

- **init.ts): add automatic initial commit after project initialization to provide a starting point for version control 🐛 fix(init.ts:** Change directory back to original after commit to ensure correct working directory ([c16d966](https://github.com/nyxb/cli/commit/c16d966))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.12

[compare changes](https://github.com/nyxb/cli/compare/v0.0.11...v0.0.12)

### 🩹 Fixes

- **init.ts:** Correct typo in project name from 'Nuxt' to 'Nyxb' in console log message ([61c8715](https://github.com/nyxb/cli/commit/61c8715))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.11

[compare changes](https://github.com/nyxb/cli/compare/v0.0.10...v0.0.11)

### 🩹 Fixes

- **package.json, init.ts): correct repository and default registry URLs from 'nyxbi' to 'nyxb' to reflect the updated organization name 🔧 fix(package.json:** Add newline at end of file to adhere to POSIX standards ([95332e7](https://github.com/nyxb/cli/commit/95332e7))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>

## v0.0.10


### 🚀 Enhancements

- **nyxbi.mjs): add new executable script for running main function 🎨 style(commands): improve code readability by adjusting indentation and line breaks 🔧 refactor(init.ts:** Restructure code for better readability and maintainability ([74e7623](https://github.com/nyxbi/cli/commit/74e7623))

### 💅 Refactors

- **eslint.config.js): enable all and typescript rules in eslint config 🔧 refactor(eslint.config.js): disable 'node/prefer-global/process' and 'no-restricted-globals' rules 🔧 refactor(package.json): rearrange 'type' and 'repository' fields for better readability 🔧 refactor(package.json): fix indentation in 'scripts' and 'devDependencies' sections ⬆️ upgrade(package.json): update '@nyxb/eslint-config' from '1.0.0-beta.11' to '1.0.0-beta.12' ➕ add(package.json:** Add '@nuxt/kit' and 'ws' to devDependencies ([40f27a8](https://github.com/nyxbi/cli/commit/40f27a8))

### 🏡 Chore

- **vscode/settings.json): comment out eslint.experimental.useFlatConfig to disable flat config support 🔧 chore(eslint.config.js): pass an empty object to nyxb() to use default eslint config ✨ feat(package.json): add detailed package information and configuration for better project understanding and usage 🔥 remove(package.json:** Remove unnecessary fields (keywords, author, license) to clean up package.json ([9682793](https://github.com/nyxbi/cli/commit/9682793))
- **vscode/settings.json): enable eslint.experimental.useFlatConfig and set eslint rules severity to error for stricter linting 🔥 remove(bin/nyxy.mjs): delete unused nyxy.mjs file 🔧 chore(tsconfig.json:** Reorder compilerOptions for better readability and consistency ([0edee17](https://github.com/nyxbi/cli/commit/0edee17))

### 🎨 Styles

- Adjust indentation for better readability across multiple files 🔧 fix(eslint.config.js): disable 'vars-on-top' rule to allow variable declarations anywhere 🔧 fix(package.json): use npx for changelogen to ensure the latest version is used ([1d27fe5](https://github.com/nyxbi/cli/commit/1d27fe5))

### ❤️ Contributors

- Nyxb <contact@nyxb.email>


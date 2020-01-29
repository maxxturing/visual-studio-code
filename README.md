# visual-studio-code

Install
https://code.visualstudio.com/docs/?dv=osx

Install extentions (blocks icon):

- Prettier
- GitLens
- ESLint
- Apollo GraphQL
- React Native Tools
- EditorConfig for VS Code

- ES7 React/Redux/GraphQL/React-Native snippets

open user settings
search format
format on save

Commits
https://www.conventionalcommits.org/en/v1.0.0/

e.g.
docs(README): installation

Description

<type>[optional scope]: <description>

[optional body]

[optional footer(s)]

--

Open Command Pallete:

`Command + Shift + P`

Install

`Shell Command: Install 'code' command in PATH`

Open Visual Studio Code from terminal

```sh
code -n .
```

--

add eslint settings (edit settings.json)

"eslint.autoFixOnSave": true,
"eslint.validate": [
"javascript",
"javascriptreact",
{
"language": "typescript",
"autoFix": true
},
{
"language": "typescriptreact",
"autoFix": true
}
],

--

After installing an extension, open the command pallete and:

> Reload Window

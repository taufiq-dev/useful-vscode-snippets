# Useful VSCode Snippets
1. [React Snippets](https://github.com/taufiq-dev/useful-vscode-snippets/edit/main/README.md#react-snippets)
## React Snippets
### React arrow function component with export
```json
{
  "React arrow function component with export": {
    "prefix": ["rafce"],
    "body": [
      "const ${1:${TM_FILENAME_BASE/(\\w*)-?/${1:/capitalize}/g}} = () => {",
      "  return <>$0</>;",
      "};",
      "",
      "export default $1;",
      ""
    ],
    "description": "Create a React arrow function component with export"
  }
}
```

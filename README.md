# Useful VSCode Snippets
1. [React Snippets](https://github.com/taufiq-dev/useful-vscode-snippets#react-snippets)
## React Snippets
**React arrow function component with export**
<br />
Removes hypens/dashes and capitalizes the words.
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
**Output**
```javascript
// my-filename.js
const MyFilename = () => {
  return <></>;
};
```

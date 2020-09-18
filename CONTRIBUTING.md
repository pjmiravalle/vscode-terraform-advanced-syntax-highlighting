# How to Contribute

This is a very early and raw implementation of a contributors guide, so bear with me.

## Development Setup
1. clone repository to local machine.
2. npm install -g js-yaml
3. open local repository in vscode
4. hit f5 to run extension locally
5. in a separate vscode window, open up desired terraform project for testing syntax highlighting changes
6. edit terraform.yaml with changes (the JSON file must not be edited directly)
7. run `js-yaml syntaxes/terraform.yaml > syntaxes/terraform.json`
8. hit green refresh button in vscode to propagate changes

## Links
- https://code.visualstudio.com/api/get-started/your-first-extension
- https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide
- http://nodeca.github.io/js-yaml/
- https://www.tutorialspoint.com/yaml/yaml_syntax_characters.htm
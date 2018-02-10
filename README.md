# PostCSS Syntax Highlighting

VSCode plugin to provide syntax highlighting for PostCSS files. It will pick up
`.css`, `.pcss`, and `.postcss` files.

## Emmet support

Include the following in your VS Code settings:

```json
{
  ...
  "emmet.includeLanguages":{
    "postcss": "css"
  },
  "emmet.syntaxProfiles": {
    "postcss": "css"
  },
  ...
}
```

## Enable for `.css` files

Include the following in your VS Code settings:

```json
{
  ...
  "files.associations": {
    "*.css": "postcss"
  }
  ...
}
```

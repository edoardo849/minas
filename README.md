# Minas

A web IDE that can be installed on any device as a PWA

## Notes

To make Typescript work, need to set:

```json
{
  "typescript.tsserver.log": "normal",
  "typescript.tsdk": "./node_modules/typescript/lib"
}
```

To make Go work, need to set:

```json
{
  "go.useLanguageServer": true,
  "go.languageServerExperimentalFeatures": {
    "diagnostics": true,
    "documentLink": true
  },
  "[go]": {
    "editor.formatOnSave": true
  }
}
```

in `settings.json`.

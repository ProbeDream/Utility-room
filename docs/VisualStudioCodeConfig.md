#### Visual Studio Code Config

众所周知现在我们比较流行的开发工具中,特别是在前端开发的过程中,使用最广泛的就是:**Visual Studio Code**

对应的一些插件系统还是比较好用的,由此记录一下我自己的 Visual Studio Code 的组件集合:

1. Auto Close Tag
2. Auto Rename Tag
3. Bracket Pair Colorizer 2
4. Chinese (Simplified) Language Pack for Visual Studio Code
5. Code Runner
6. Code Spell Checker
7. Color Info
8. Debugger for Chrome
9. filesize
10. GitHub Pull Requests
11. gitignore
12. GitLens — Git supercharged
13. Import Cost
14. indent-rainbow
15. IntelliSense for CSS class names in HTML
16. language-stylus
17. Manta's Stylus Supremacy
18. Markdown Preview Enhanced
19. Path Intellisense
20. Prettier - Code formatter
21. SVG Viewer
22. Vetur
23. Visual Studio IntelliCode
24. vscode-icons
25. Image preview
26. CSS Peek
27. Quokka.js
28. Browser Preview
29. javascript Booster
30. REST Client
31. Polacode
32. TODO Highlight
33. Version Lens
    关于 Visual Studio Code 的设置如下所示:

```json
{
  "window.zoomLevel": -1,
  // 以像素为单位控制字号。
  "editor.fontSize": 18,
  // 控制边栏的位置。它可显示在工作台的左侧或右侧。
  "workbench.sideBar.location": "left",
  // 控制工作台中活动栏的可见性。
  "workbench.activityBar.visible": true,
  "git.autofetch": true,
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontFamily": "Consolas",
  // "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
  "terminal.integrated.shell.windows": "E:\\DevelopmentUtil\\Git\\usr\\bin\\bash.exe",
  "editor.suggestSelection": "first",
  // "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "files.associations": {
    "*.cjson": "jsonc",
    "*.wxss": "css",
    "*.wxs": "javascript",
    "*.vue": "vue"
  },
  "emmet.includeLanguages": {
    "wxml": "html"
  },
  "editor.fontFamily": "Source Code Pro,Source Code Variable,Monaco,Consolas,Menlo, 'Courier New', monospace",
  "debug.console.fontFamily": "Source Code Pro",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // Vim Config list
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "breadcrumbs.enabled": true,
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "terminal.external.windowsExec": "D:\\DevelopmentUitl\\git\\bin\\bash.exe",
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "cSpell.enabledLanguageIds": [
    "asciidoc",
    "c",
    "cpp",
    "csharp",
    "css",
    "git-commit",
    "gitignore",
    "go",
    "handlebars",
    "html",
    "jade",
    "java",
    "javascriptreact",
    "json",
    "jsonc",
    "latex",
    "less",
    "markdown",
    "php",
    "plaintext",
    "pug",
    "python",
    "restructuredtext",
    "rust",
    "scala",
    "scss",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ],
  "markdown.preview.fontFamily": "FiraCode-Retina,Source Code Pro, BlinkMacSystemFont, 'Ubuntu', 'Droid Sans', sans-serif",
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "files.defaultLanguage": "html",
  "workbench.statusBar.visible": true,
  "files.autoSave": "onFocusChange",
  "editor.find.autoFindInSelection": true,
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": false
  },
  "vsicons.dontShowNewVersionMessage": true,
  "editor.renderWhitespace": "none",
  "editor.renderControlCharacters": true,
  "path-intellisense.autoSlashAfterDirectory": true,
  "path-intellisense.extensionOnImport": true,
  "path-intellisense.showHiddenFiles": true,
  "bracket-pair-colorizer-2.colors": ["Gold", "Orchid", "LightSkyBlue"],
  "vetur.format.scriptInitialIndent": true,
  "vetur.format.styleInitialIndent": true,
  "html-css-class-completion.enableEmmetSupport": true,
  "explorer.confirmDelete": false,
  "gitlens.views.repositories.files.layout": "list",
  "workbench.iconTheme": "vscode-icons",
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "browser-preview.chromeExecutable": "E:\\ToolCollection\\Chrome\\chrome.exe",
  "extensions.ignoreRecommendations": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

# Sublime

## 常用插件

* Material Theme
* Golang Build
* SublimeCodeIntel
* A File Icon
* Color Highlighter
* Bracket Highlighter
* All Autocomplete

# VSCode

## 常用插件
* Atom Material Theme
* Atom One Dark Theme
* One Dark Pro
* Better Comments
* Better TOML
* Bracket Pair Colorizer
* Go
* C/C++
* C/C++ Clang Command Adapter
* C++ Intellisense
* CMake
* CMake Tools
* Code Runner
* filesize
* Git History
* gitignore
* GitLens — Git supercharged
* Markdown All in One
* Output Colorizer
* Path Intellisense
* Remote VSCode
* Vim
* VSCode Great Icons
* vscode-proto3

## 配置文件

```
{
    "editor.fontSize": 14,
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "workbench.colorTheme": "One Dark Pro",
    "workbench.iconTheme": "vscode-great-icons",
    // golang setting
    "go.goroot": "/usr/local/Cellar/go/1.12.6/libexec",
    "go.gopath": "/Users/didi/ddcode:/Users/didi/go",
    "go.formatTool": "goimports",
    "go.useLanguageServer": true,
    // cpp setting
    "C_Cpp.clang_format_fallbackStyle": "{ BasedOnStyle: Google, UseTab: Never, IndentWidth: 4, TabWidth: 4}",
    "cmake.configureOnOpen": true,
    "explorer.confirmDragAndDrop": false,
    "window.zoomLevel": 0,
    "explorer.sortOrder": "type",
    "explorer.confirmDelete": false,
    "C_Cpp.updateChannel": "Insiders",
}
```
# Instalation
1. Unzip this pack inside your unity project
2. Rename _gitignore to .gitignore
3. Install recommended VS Code extensions.

    VS Code will show pop-ups to install recommended extensions that are not already in the workspace.

    You can also `Ctrl + Shift + p`, go to `Extensions: Show Recomended Extensions` and install them from there.
4. Remove this README for your project and add your own

# Contents

## Git Ignores
```
_gitignore
```
Common ignored files for git projects. Needs to have the _gitignore file renamed to .gitignore

___

## Unity Analyzers
```
Nuget/microsoft.unity.analyzers.1.11.1/Microsoft.Unity.Analyzers.dll
omnisharp.json
```
Adds several Unity-specific code diagnostics and removes general C# diagnostics that do not apply to Unity projects.

___

## VS Code configuration
```
.vscode/settings.json
```

- Excludes common files and folders from VS Code Explorer.
- Applies Eppz color theme and vscode-icons.

___

## VS Code recommended extensions
```
.vscode/extensions.json
```

VS Code will show pop-ups to install recommended extensions that are not already in the workspace.

You can also `Ctrl + Shift + p`, go to `Extensions: Show Recomended Extensions` and install them from there.

- **C#**: C# language support
- **Unity Debug**: Needed for debugging Unity games with Code
- **Git Lens**: Improves Git tab
- **Eppz**: Color theme
- **Project Manager**: For managing projects and git projects
- **TODO Hightlight** & **TODO Tree**: TODO and similar tag management
- **Unity Snippets**: Enables autocomplete for Monobehaviour messages (Start, Update, FixedUpdate...)
- **Unity Tools**:
- **Unity Meta Files Watch**: Watches asset files and moves .meta files when their base files are moved inside code.
- **VSCode Icons**: Improves Code file icons
- **Editorconfig**: Cross-editor config files

___

## Editorconfig
```
editorconfig.json
```

Works with *editorconfig* Code extension. Helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
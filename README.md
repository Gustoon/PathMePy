# PathMePy
A tool to add scripts to Path

## Installation
You have to install the package by moving the `PathMePy.py` file into your project.

## Content
You need to import this package with `import PathMePy`
This packages add four functions : 
`PathMePyDir(path)`,
`PathMePyUserScriptFolder()`,
`IsAlreadyOnPath(path)`,
`UserScriptFolderIsAlreadyOnPath()`,
two variables `Current_Path` and `Current_Path_Formated`

## Explanation
`PathMePyDir(path)` function is for temporaly add a directory in your user PATH variable,
`PathMePyUserScriptFolder()` function is for add the Python User Script Folder to the user PATH variable,
`IsAlreadyOnPath(path)` function return if an element is on the PATH or not,
`UserScriptFolderIsAlreadyOnPath()` function return if the User Script folder is on the PATH or not,
`Current_Path` is a variable with the current path,
`Current_Path_Formated` is a formatted version of `Current_Path` that changes each PATH separator with a newline.

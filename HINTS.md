# Hints

## Useful links for creating Syntax Highlighting for VSCode

https://github.com/onerobotics/vim-karel/blob/master/syntax/karel.vim  
http://www.onerobotics.com/posts/2013/introduction-to-karel-programming/

https://code.visualstudio.com/docs/extensions/yocode#_new-language-support  
https://code.visualstudio.com/docs/extensionAPI/language-support

https://stackoverflow.com/questions/28592093/converting-emacs-vim-highlighting-to-textmate-for-sublimetext

https://manual.macromates.com/en/language_grammars

https://raw.githubusercontent.com/martinring/tmlanguage/master/tmlanguage.json

https://github.com/kkos/oniguruma/blob/master/doc/RE  
https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expression-language-quick-reference

https://github.com/Microsoft/vscode/blob/master/extensions/javascript/syntaxes/JavaScript.tmLanguage.json



> Now that we have our matches, we need our colors. The color associated with a match is specified by the name attribute. The color value of this name is defined by the current theme used by VS Code. Therefore, to consult all the available colors, you can open a default theme JSON file. It is located under the installation folder of VS Code (on windows, under AppData). For example, you can search for *dark_vs.json*, which is located under *app/extensions/defaults/themes/*. Therefore, it is not possible to create custom colors names for your language, unless you also create a custom theme for it.
>
>  \- http://gcthesoftwareengineer.com/2017/01/how-to-create-custom-syntax-highlighting-in-a-visual-studio-code-extension/

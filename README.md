# PhpStorm Live Templates 

1. Find config directory of your PHPStorm IDE by studying [Directories used by the IDE to store settings, caches, plugins and logs](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs) guide.
2. Explore the list of default IDE directories, by following [Tuning PHPStorm](https://www.jetbrains.com/help/phpstorm/tuning-the-ide.html) guide - Under section **Configuration directory** you shall find the comprehensive list, while below are the most interesting options:

Directory | User settings
----------|---------
templates | User-defined [live templates](https://www.jetbrains.com/help/phpstorm/using-live-templates.html)
codestyles | [Code style schemes](https://www.jetbrains.com/help/phpstorm/configuring-code-style.html)
colors | Customized [editor color and font schemes](https://www.jetbrains.com/help/phpstorm/configuring-colors-and-fonts.html)
fileTemplates | User-defined [file templates](https://www.jetbrains.com/help/phpstorm/using-file-and-code-templates.html) which pertain to the entire PhpStorm workspace
filetypes | User-defiend [file types](https://www.jetbrains.com/help/phpstorm/creating-and-registering-file-types.html)
inspection | [Code inspection profiles](https://www.jetbrains.com/help/phpstorm/code-inspection.html)
keymaps | [Customized keyboard shortcuts](https://www.jetbrains.com/help/phpstorm/configuring-keyboard-and-mouse-shortcuts.html)

3. Copy `templates/Markdown.xml` to your `IDE config/templates` directory (example for MacOS below)
```
cd /tmp
git clone git@github.com:tekmi/phpstorm-settings.git
cp /tmp/phpstorm-settings/templates/Markdown.xml /Users/tekmi/Library/Preferences/PhpStorm2018.1/templates
```

4. Enjoy writing in Markdown (I assume you have [Mardkown Plugin](https://plugins.jetbrains.com/plugin/7793-markdown-support) installed) with new Live Templates from TekMi.

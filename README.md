# sublime-user-settings
Sublime Text User Settings

Preferences -> Settings User

# Packages
- Indent XML  - https://packagecontrol.io/packages/Indent%20XML - top
- Pretty JSON - Minify/Prettify JSON and converts to XML        - ganz gut
- Terminal    - Open a Terminal at the current file or project  - top
- Trailing Spaces - Unnötige Leerzeichen am Ende anzeigen       - top
- Icon Fonts  - Code-Completion for Font Awesome                - top
- CopyWithLineNumbersReloaded - Kopiert mit Zeilennummern       - top
- BracketHighlighter - Shows brackets beside line numbers       - top
- Markdown Syntax Highlighting - https://packagecontrol.io/packages/MarkdownEditing - noch nicht probiert, aber empfohlen
- Ascii Decorator - https://packagecontrol.io/packages/ASCII Decorator - top
- Theme Soda - https://packagecontrol.io/packages/Theme%20-%20Soda - top (ändert nur das UI Theme, nicht den Syntaxbereich)
- https://packagecontrol.io/packages/PackageResourceViewer    - top (zum Anzeigen von Package Inhalten, z.B. Theme files)
- A File Icon - https://packagecontrol.io/packages/A%20File%20Icon - top (fügt der Sidebar File Icons zu)

# Installation JS Lint
1. Install Package SublimeLinter in Sumbline Text (via Package Control)
2. Install SublimeLinter-jshint (via Package Control, there should be many linters beginning with sublimelinter-)
3. Install jshint via NPM (npm install -g jshint). This installs jshint globally

# Getting the sidebar dark (so that it fits Dark Solarized theme)
Unclear how exactly that worked.

I think the file "Default.sublime-theme" needs to be placed in 
C:\Users\<username>\AppData\Roaming\Sublime Text 3\Packages\User

Maybe "Soda Dark 3.sublime-theme" is also required but that should be a package that can be installed.

Some goodies created by our team and friends.

	cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
	git clone git://github.com/tapronto/sublime.git Tapronto

Themes: Monokai Soda Dark + dark sidebar
-----

This is a mod based on some themes around, including the [Monokai Soda](https://github.com/mrlundis/Monokai-Dark-Soda.tmTheme) theme.

- Copy the Default.sublime-theme file to your *Packages/User* folder
- Add the color scheme to your preferences:

`"color_scheme": "Packages/Tapronto/themes/Monokai Soda.tmTheme"`

Symfony2
-----

Snippets for SF2, Twig and Doctrine.

Tab triggers:

- Doctrine column annotation snippet: `col`
- Twig path: `path`
- Twig i18n block: `trans`

Key bindings:

- Twig i18n string: `{ "keys": ["super+alt+t"], "command": "insert_snippet", "args": {"name": "Packages/Tapronto/Symfony2/trans-sf.sublime-snippet"} },`

PHP
-----

Tab triggers:

- print_r + pre snippet: `dv`
- Array params snippet: `=>`

HTML
-----

Tab triggers:

- Link snippet: `a`
- Dummy link snippet: `ad`
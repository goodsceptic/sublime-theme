# goodsceptic sublime text theme

Install:

```sh
cd path/to/your/sublime/packages
git clone https://github.com/goodsceptic/sublime-theme.git goodsceptic-theme
```

You'll also need the fonts
[Inter](https://rsms.me/inter/) and
[JetBrains Mono](https://www.jetbrains.com/lp/mono/)
installed on your system, which are used by the UI theme.


## Use

Open the command prompt in Sublime (⇧⌘P), type "goodsceptic:" and select an option.

- `lights off` — enable dark theme
- `lights on` — enable bright theme
- `toggle dark/light` — toggle. Shortcut: ⌥⌘L


### Recommended settings

In your `Packages/User/Preferences.sublime-settings`:

```js
"font_size": 13,
"font_options": ["no_calt"],
"line_padding_bottom": 1,
"line_padding_top": 0,
"highlight_line": false,
"show_tab_close_buttons": false,
"fold_buttons": false,
"wide_caret": false,
"caret_style": "blink",
```
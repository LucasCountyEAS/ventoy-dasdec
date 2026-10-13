<h1 align="center">ventoy-dasdec</h1>

<h3 align="center">A simple DASDEC-style theme for <a href="https://www.ventoy.net/">Ventoy</a>.</h3>


<img width="1025" height="770" alt="what youll probably see hopefully" src="https://github.com/user-attachments/assets/5821df4b-32dd-40f1-ae51-634f112b69f9" />

## Installation

1. Download the latest zip from the [Releases](../../releases) page, or clone this repo.
2. Copy the `ventoy` and `grub` folders to the **root of your Ventoy USB's data partition** (the large one), merging with any existing folders.
3. Boot from the drive. The theme loads automatically.

### Already have a `ventoy.json`?

Copying the folders will overwrite your existing `/ventoy/ventoy.json`. If you use it for plugins, auto-install, persistence, etc., back it up first and add the `theme` block to your own file instead:

```json
{
  "theme": {
    "file": "/grub/themes/ventoy/theme.txt"
  }
}
```

If you put the theme somewhere else, change the path to match. See the
[Ventoy theme plugin docs](https://www.ventoy.net/en/plugin_theme.html) for more options
(display mode, fonts, resolution, etc.).

<img width="2880" height="2160" alt="how it should look on real hardware" src="https://github.com/user-attachments/assets/17092fa3-6852-4bef-bfda-380613ccd4ce" />


## Credits

- Ventoy by [longpanda](https://github.com/ventoy/Ventoy)
- Font: Luxi Mono (Bigelow & Holmes)
- The Making: [LucasCountyEAS](https://youtube.com/@LucasCountyEAS) (Rukasu)

> i gotta make myself a website one day
*Unofficial theme, not affiliated with or endorsed by Digital Alert Systems.*

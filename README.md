# moss_zola

![screenshot01](/static/images/ss01.png)


A simple theme for [zola](https://getzola.org)

Features:
- simple & clean
- mobile-friendly
- MathJax support

Demo site is TODO

Forked from [emily_zola_theme](https://github.com/kyoheiu/emily_zola_theme)
## Usage

```
cd YOUR_SITE_DIRECTORY/themes
git clone https://github.com/JohnEdChristensen/moss_zola
```

and set the theme-name in `config.toml` to `moss_zola`.

```
theme = "moss_zola"
```

## example articles

In `YOUR_SITE_DIRECTORY/themes/moss_zola/content`.

## MathJax support

To use MathJax, add the following lines to the front matter in `.md` file. `[extra]` is mandatory:

```
[extra]
math = true
```

## How to customize
In addition to default values, you can customize following parts easily:

- author name (appears in footer)
- header icon (appears in header)
- favicon
- header icon size (default width: 70px)
- number of posts in `index.html` (default 5)

Set your own in `themes/moss_zola/theme.toml`, or to overwrite, copy `[extra]` block, paste it into your `config.toml` and edit.

# fancy-font

## About fancy-font

fancy-font is a simple command-line based project that converts text into different Unicode fonts.

*Date of creation:* `September 17, 2019`

Some examples of the fonts are given below:
- ๐๐ฉ๐ก๐ข๐ง๐ฑ ๐จ๐ ๐๐ฅ๐๐๐ค ๐ช๐ฎ๐๐ซ๐ญ๐ณ, ๐ฃ๐ฎ๐๐ ๐ ๐ฆ๐ฒ ๐ฏ๐จ๐ฐ.
- ๐บ๐๐๐๐๐ ๐๐ ๐๐๐๐๐ ๐๐๐๐๐๐, ๐๐๐๐๐ ๐๐ ๐๐๐.
- ๐ข๐น๐ฑ๐ฒ๐ท๐ ๐ธ๐ฏ ๐ซ๐ต๐ช๐ฌ๐ด ๐บ๐พ๐ช๐ป๐ฝ๐, ๐ณ๐พ๐ญ๐ฐ๐ฎ ๐ถ๐ ๐ฟ๐ธ๐.
- ๊ฑแดสษชษดx แด๊ฐ สสแดแดแด วซแดแดสแดแดข, แดแดแดษขแด แดส แด แดแดก.
- ๐๐ฑ๐ฉ๐ช๐ฏ๐น ๐ฐ๐ง ๐ฃ๐ญ๐ข๐ค๐ฌ ๐ฒ๐ถ๐ข๐ณ๐ต๐ป, ๐ซ๐ถ๐ฅ๐จ๐ฆ ๐ฎ๐บ ๐ท๐ฐ๐ธ.
- ๐๐๐๐๐๐ก ๐๐ ๐๐๐๐๐ ๐๐๐๐๐๐ฃ, ๐๐๐๐๐ ๐๐ข ๐๐๐ .

## Footnotes

Some Unicode fonts do not support lowercase characters, while some other fonts do not support ascii digits. Such characters **are not** mapped to the font style being used.

## Run

To use, clone the repository on your device, navigate to the folder. Make the following edits to `main.py`:
- On [Line 26](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L26), set `STRING` to your desired text
- On [Line 29](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L29), set `font_numbers` to a set containing the font-numbers of your desired fonts
- To check what font corresponds to what number, look up the dictionary `STYLE` defined on [Line 31](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L31)

Execute:

```
python3 main.py
```

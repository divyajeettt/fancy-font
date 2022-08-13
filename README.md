# fancy-font

## About fancy-font

fancy-font is a simple command-line based project that converts text into different Unicode fonts. \
*Date of creation:* `September 17, 2019`

Some examples of the fonts are given below:
- 𝐒𝐩𝐡𝐢𝐧𝐱 𝐨𝐟 𝐛𝐥𝐚𝐜𝐤 𝐪𝐮𝐚𝐫𝐭𝐳, 𝐣𝐮𝐝𝐠𝐞 𝐦𝐲 𝐯𝐨𝐰.
- 𝑺𝒑𝒉𝒊𝒏𝒙 𝒐𝒇 𝒃𝒍𝒂𝒄𝒌 𝒒𝒖𝒂𝒓𝒕𝒛, 𝒋𝒖𝒅𝒈𝒆 𝒎𝒚 𝒗𝒐𝒘.
- 𝓢𝓹𝓱𝓲𝓷𝔁 𝓸𝓯 𝓫𝓵𝓪𝓬𝓴 𝓺𝓾𝓪𝓻𝓽𝔃, 𝓳𝓾𝓭𝓰𝓮 𝓶𝔂 𝓿𝓸𝔀.
- ꜱᴘʜɪɴx ᴏꜰ ʙʟᴀᴄᴋ ǫᴜᴀʀᴛᴢ, ᴊᴜᴅɢᴇ ᴍʏ ᴠᴏᴡ.
- 𝘚𝘱𝘩𝘪𝘯𝘹 𝘰𝘧 𝘣𝘭𝘢𝘤𝘬 𝘲𝘶𝘢𝘳𝘵𝘻, 𝘫𝘶𝘥𝘨𝘦 𝘮𝘺 𝘷𝘰𝘸.
- 𝚂𝚙𝚑𝚒𝚗𝚡 𝚘𝚏 𝚋𝚕𝚊𝚌𝚔 𝚚𝚞𝚊𝚛𝚝𝚣, 𝚓𝚞𝚍𝚐𝚎 𝚖𝚢 𝚟𝚘𝚠.

## Footnotes

Some Unicode fonts do not support lowercase characters, while some other fonts do not support ascii digits. Such characters <b>are not</b> mapped to the font style being used.

## Run

To use, clone the repository on your device, navigate to the folder. Make the following edits to main.py:
- On [Line 26](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L26), set `STRING` to your desired text
- On [Line 29](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L29), set `font_numbers` to a set containing the font-numbers of your desired fonts
- To check what font corresponds to what number, look up the dictionary `STYLE` defined on [Line 31](https://github.com/divyajeettt/fancy-font/blob/37282ac4336622066197b8a5d59656ec160e7f8a/main.py#L31)

Execute:

```
python3 main.py
```

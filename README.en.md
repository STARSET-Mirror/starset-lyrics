# STARSET Lyrics & Translation Collection

## License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1">

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">Unless otherwise stated, <a property="dct:title" rel="cc:attributionURL" href="https://git.owu.one/starset-mirror/starset-lyrics">STARSET Lyrics & Translation Collection</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0</a> and authorized with <a href="#additional-terms">additional terms</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://mirror.starset.fans">STARSET Mirror</a>.

### Additional Terms

- STARSET Mirror and individual authors of translation in this repo reserve the right to redistribute their own translations under any other license or terms.
- STARSET Mirror reserves the right to add, remove, and modify additional terms.

### Exceptions

- The English lyrics listed in this repository are for reference only. The copyright of the original lyrics belongs to their respective creators and rights holders.

## Format

### Content Format

- All lyrics and translations are in `LRC` format encoded with `UTF-8`.
- Timestamp precision is in milliseconds.
- Lyrics and translations do not contain blank lines.
- Example:
  ```lrc
  [ti: Title]
  [ar: Artist]
  [al: Album]
  [by: Translator (if any)]
  [00:01.386] First line
  [00:08.523] Second line
  [00:16.337] Third line
  ```

### Naming Convention 

- Path structure:`/language-code/album-name/two-digit-number-song title(-translator).lrc`
- `Translator` is optional, default translation versions for English lyrics and other languages do not include this part.

## Translation Languages 

- [x] Simplified Chinese(./zh-CN)
- [ ] Traditional Chinese

Each language may have multiple translations of the same song, one of which will be selected as the default translation.

## Default Translation Version 

The default translation version is a translation that best meets the following criteria among existing translations:

 - The translation is accurate, vivid and conforms to the principles of "faithfulness, expressiveness, elegance"
 - The translation is consistent with STARSET's worldview

## Contribution

- You can submit new translations through any of the following methods:

  - [Fork](https://git.owu.one/repo/fork/13) your own repository according to requirements outlined in the [Format](#format) section. Then initiate a Pull Request.
  - Create a new issue [here](https://git.owu.one/starset-mirror/starset-lyrics/issues)
  - Contact us via [Discord](https://discord.gg/zhEqePWneb) or [Email](mailto:mirror@starset.fans).

- If you wish to change the default translation version, please submit a new issue ticket at [here](https://git.owu.one/starset-mirror/starset-lyrics/issues).
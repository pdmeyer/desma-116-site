Cloned from: <https://github.com/pdmeyer/desma-116-site>

Hugo Tutorial:
<https://www.staticguide.org/>

Adding audio to Hugo
<https://www.johnarroyo.com/2021/02/adding-audio-to-hugo/>

Hextra

- getting started - <https://imfing.github.io/hextra/docs/getting-started/>
- deploy - <https://imfing.github.io/hextra/docs/guide/deploy-site/>
- organize files - <https://imfing.github.io/hextra/docs/guide/organize-files/>
- configuration - <https://imfing.github.io/hextra/docs/guide/configuration/>
- markdown - <https://imfing.github.io/hextra/docs/guide/markdown/>
- shortcodes - <https://imfing.github.io/hextra/docs/guide/shortcodes/>

Convert png to jpg

```sh
mkdir -p jpg && magick mogrify -format jpg -path jpg -resize '600x>' -background white -alpha remove -alpha off -quality 85 *.png
```

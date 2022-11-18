---
language:
- en
tags:
- stable-diffusion
- text-to-image
license: creativeml-openrail-m
inference: false

---

# Diffusion model
This model is trained with high quality and detailed anime images.

# Sample generations
This model works well on anime and landscape generations.<br>
Anime:<br>
There are some sample generations:<br>

```
Positive:a girl, Phoenix girl, fluffy hair, war, a hell on earth, Beautiful and detailed explosion, Cold machine, Fire in eyes, burning, Metal texture, Exquisite cloth, Metal carving, volume, best quality, normal hands, Metal details, Metal scratch, Metal defects, masterpiece, best quality, best quality, illustration, highres, masterpiece, contour deepening, illustration,(beautiful detailed girl),beautiful detailed glow
Negative:lowres, bad anatomy, ((bad hands)), text, error, ((missing fingers)), cropped, jpeg artifacts, worst quality, low quality, signature, watermark, blurry, deformed, extra ears, deformed, disfigured, mutation, censored, ((multiple_girls))
Steps: 20, Sampler: DPM++ 2S a, CFG scale: 8, Seed: 919456124, Size: 704x896
```
<img src=https://imgur.com/EIEPogJ.png width=75% height=75%>


```
Positive:(1girl), cute, walking in the park, (night), full moon, north star, blue shirt, red skirt, detailed shirt, jewelry, autumn, dark blue hair, shirt hair, (magic:1.5), beautiful blue eyes
Negative: lowres, bad anatomy, ((bad hands)), text, error, ((missing fingers)), cropped, jpeg artifacts, worst quality, low quality, signature, watermark, blurry, deformed, extra ears, deformed, disfigured, mutation, censored, ((multiple_girls))
Steps: 35, Sampler: Euler a, CFG scale: 9, Seed: 296195494, Size: 768x960
```
<img src=https://imgur.com/gudKxQe.png width=75% height=75%>

```
Positive:night , ((1 girl)), alone, masterpiece, 8k wallpaper, highres, absurdres, high quality background, short hair, black hair, multicolor hair, beautiful frozen village, (full bright moon), blue dress, detailed dress, jewelry dress, (magic:1.2), blue fire, blue eyes, glowing eyes, fire, ice goddess, (blue detailed beautiful crown), electricity, blue electricity, blue light particles
Negative: lowres, bad anatomy, ((bad hands)), text, error, ((missing fingers)), cropped, jpeg artifacts, worst quality, low quality, signature, watermark, blurry, deformed, extra ears, deformed, disfigured, mutation, censored, ((multiple_girls))
Steps: 20, Sampler: DPM++ 2S a Karras, CFG scale: 9, Seed: 2118767319, Size: 768x832
```
<img src=https://imgur.com/lJL4CJL.png width=75% height=75%>

Want to generate some nice backgrounds? No problem:
```
Positive: above clouds, mountains, (night), full moon, castle, huge forest, forest between mountains, beautiful, masterpiece
Negative: lowres, bad anatomy, ((bad hands)), text, error, ((missing fingers)), cropped, jpeg artifacts, worst quality, low quality, signature, watermark, blurry, deformed, extra ears, deformed, disfigured, mutation, censored, ((multiple_girls))
Steps: 20, Sampler: DPM++ 2S a Karras, CFG scale: 9, Seed: 83644543, Size: 896x640
```
<img src=https://imgur.com/XfxAx0S.png width=75% height=75%>

## Disclaimer
Some prompts might not work perfectly (mainly colors), so add some more prompts for it to work, or try these -->().
Usually they help. Also works well with img2img if you want to add detail.

## License

This model is open access and available to all, with a CreativeML OpenRAIL-M license further specifying rights and usage.
The CreativeML OpenRAIL License specifies: 

1. You can't use the model to deliberately produce nor share illegal or harmful outputs or content 
2. The authors claims no rights on the outputs you generate, you are free to use them and are accountable for their use which must not go against the provisions set in the license
3. You may re-distribute the weights and use the model commercially and/or as a service. If you do, please be aware you have to include the same use restrictions as the ones in the license and share a copy of the CreativeML OpenRAIL-M to all your users (please read the license entirely and carefully)
[Please read the full license here](https://huggingface.co/spaces/CompVis/stable-diffusion-license)
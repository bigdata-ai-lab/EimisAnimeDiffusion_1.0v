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
This model is trained with high quality and detailed anime images through fine-tuning.

# Sample generations
This model works well on anime and landscape generations.
Anime:
There are some sample generations:
```
Positive:(1girl), cute, walking in the park, (night), full moon, north star, blue shirt, red skirt, detailed shirt, jewelry, autumn, dark blue hair, shirt hair, (magic:1.5), beautiful blue eyes
Negative: lowres, bad anatomy, ((bad hands)), text, error, ((missing fingers)), cropped, jpeg artifacts, worst quality, low quality, signature, watermark, blurry, deformed, extra ears, deformed, disfigured, mutation, censored, ((multiple_girls))
Steps: 35, Sampler: Euler a, CFG scale: 9, Seed: 296195494, Size: 768x960
```
<img src=https://imgur.com/gudKxQe.png width=75% height=75%>


## Disclaimer
Some prompts might not work perfectly (mainly colors, backgrounds), so add some more prompts for it to work, or try these -->().
Usually they help.

## License

This model is open access and available to all, with a CreativeML OpenRAIL-M license further specifying rights and usage.
The CreativeML OpenRAIL License specifies: 

1. You can't use the model to deliberately produce nor share illegal or harmful outputs or content 
2. The authors claims no rights on the outputs you generate, you are free to use them and are accountable for their use which must not go against the provisions set in the license
3. You may re-distribute the weights and use the model commercially and/or as a service. If you do, please be aware you have to include the same use restrictions as the ones in the license and share a copy of the CreativeML OpenRAIL-M to all your users (please read the license entirely and carefully)
[Please read the full license here](https://huggingface.co/spaces/CompVis/stable-diffusion-license)
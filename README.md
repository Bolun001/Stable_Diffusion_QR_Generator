# Stable_Diffusion_QR_Generator
QR Generator Settings
Comes from Twitter [@](https://twitter.com/bitfool1/status/1669555928952377345)https://twitter.com/bitfool1/status/1669555928952377345

Preview requirements: 
  Checkpoints: Dreamshaper_6
  Controlnet
  inpaint_global_harmonious
    control_v1p_sd15_brightness [5f6aa6ed]
    control_v11f1e_sd15_tile[a371b31b]
QR Generator: https://zh.qr-code-generator.com/
Keywords: masterpiece, best quality, mecha, no humans, black armor, blue eyes, science fiction, fire, laser canon beam, war, conflict, destroyed city background
Negative: UnrealisticDream, FastNegativeEmbedding



Stable Diffusion text2img setting:
Sampling method: DPM++2M Karras
Sampling step: 20

Controlnet 0 setting: Enable
inpaint_global_harmonious
    control_v1p_sd15_brightness [5f6aa6ed]
Control Weight  0.35

Controlnet 1 setting: Enable
inpaint_global_harmonious
    control_v11f1e_sd15_tile[a371b31b]

Control Weight
0.65

Starting Control Step
0.35

Ending Control Step

Results:
![image](https://github.com/Bolun001/Stable_Diffusion_QR_Generator/assets/99233679/b43bf8a7-7e0d-4ee7-b959-6c296883ff15)

# wyrde-comfyui-workflows
some wyrde workflows for comfyUI

ComfyUI is found at https://github.com/comfyanonymous/ComfyUI

## Folders

* [basics:](./basics) some low-scale workflows. Good ways to start out.
* [hr-fix-upscale:](./hr-fix-upscale) workflows utilizing Hi-Res Fixes and Upscales.
* [misc:](./misc) various odds and ends.
* [others:](./others) workflows made by other people I particularly like. Or had the urge to fiddle with.
* [templates](./templates) some handy templates for comfyui

## Custom Nodes and Extensions

The custom nodes and extensions I know about.

### List
* ltdrdata's custom nodes
  * [Comfy Manager](https://github.com/ltdrdata/ComfyUI-Manager)
    * help organize and install various custom nodes (under development)
  * https://github.com/ltdrdata/ComfyUI-Impact-Pack
    * Lots of nodes tha do impressive things
* [WAS node suite](https://github.com/WASasquatch/was-node-suite-comfyui)
  * development has resumed
* https://github.com/lilly1987/ComfyUI_node_Lilly
  * Lots of amazing things which are beyond me
* https://github.com/lilly1987/ComfyUI-workflow
  * more workflows!
* https://github.com/guoyk93/yk-node-suite-comfyui
* https://github.com/pythongosssss/ComfyUI-Custom-Scripts
  * useful and helpful UI additions. Many are added to comfyUI so keep an eye on them
* https://github.com/Fannovel16/comfy_controlnet_preprocessors
  * Have a ModuleNotFoundError? [check this out](https://github.com/wyrde/wyrde-comfyui-workflows/edit/main/basics/controlnet_install.md)
* https://github.com/diontimmer/ComfyUI-Vextra-Nodes
* https://github.com/Davemane42/ComfyUI_Dave_CustomNode
* https://github.com/diffus3/ComfyUI-extensions
  * I think most of these are in comfyui now
* https://github.com/m957ymj75urz/ComfyUI-Custom-Nodes
* https://github.com/omar92/ComfyUI-QualityOfLifeSuit_Omar92
  * much of the same ideas as WAS suit but in a different direction
* https://github.com/hnmr293/ComfyUI-nodes-hnmr
* [blenderneko's nodes](https://github.com/BlenderNeko)
  * https://github.com/BlenderNeko/ComfyUI_ADV_CLIP_emb
    * advanced clip encoding (weighting changes)
  * https://github.com/BlenderNeko/ComfyUI_Cutoff
    * cut-off control
* https://github.com/ailex000/ComfyUI-Extensions/
  * image box/lightbox for previews of generated images
* https://github.com/BadCafeCode/masquerade-nodes-comfyui
  * Masquerade Nodes 
* https://github.com/AIGODLIKE/ComfyUI-BlenderAI-node
  * Blender integration for comfyui

### CivitAI

* Many custom nodes are provided as packages on [civitai](https://civitai.com/).
* Use the "other" type in filters or search with the [comfyui](https://civitai.com/?query=comfyui) tag.  
<img src="https://user-images.githubusercontent.com/9657443/232229734-e1e662f5-d534-413d-9a05-24a09abfef20.png" width="20%" align="middle">

### ComfyResources Project
* Many custom projects are listed at [ComfyResources](https://github.com/wyrde/ComfyResources)
* Developers with githtub accounts can easily add to the list

### Installing Custom Nodes and Extensions

* Some more information on installing custom nodes and extensions in [basics](./basics)
* Most have instructions in their repositories or on civit.
* If you install custom nodes, keep an eye on comfyui PRs. Many end up in the UI.

## Useful things
* Upscale Database: https://upscale.wiki/wiki/Model_Database
  * note: stick to the universals unless there's one that fits specific needs
  * I often use 2xPNSR for quick upscales (first line, in source section).
  * lollypop x4 is my favorite for illustration style images.
* [A handy chart of aspect ratios](https://user-images.githubusercontent.com/9657443/231819299-77de2080-7b04-4512-9922-56faec2596b8.png) from a [reddit post](https://www.reddit.com/r/StableDiffusion/comments/10wqv7r/when_it_comes_to_printing_converting_resolutions/)
* [MisterRuffian's Latent Artist & Modifier Encyclopedia](https://docs.google.com/spreadsheets/d/1_jgQ9SyvUaBNP1mHHEzZ6HhL_Es1KwBKQtnpnmWW82I/edit#gid=1807667703)
* Pickel Scanner: https://github.com/mmaitre314/picklescan
* [Stable Diffusion Prompt Reader](https://github.com/receyuki/stable-diffusion-prompt-reader)

## inject SD into the brain
* https://www.youtube.com/@OlivioSarikas
* https://rentry.org/safetensorsguide
* https://rentry.org/sdvae
* List of nodes and examples of use https://comfyui.creamlab.net/nodes (Japanese)

## More SD resources
* https://civitai.com/ (when they're not breaking it)
* https://huggingface.co/

## Useful Things
* [XNView](https://www.xnview.com/en/) a great, light-weight and impressively capable file viewer. It shows the workflow stored in the exif data (View→Panels→Information). Also has favorite folders to make moving and sortintg images from `./output` easier. There may be something better out there for this, but I've not found it.
* [Powertoys](https://learn.microsoft.com/en-us/windows/powertoys/) make windows experience more pleasant. Especially [windows terminal](https://learn.microsoft.com/en-us/windows/terminal/)
* [process explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) get a better look at what is going on. Add the "GPU Dedicated Bytes" column and see what is eating away VRAM

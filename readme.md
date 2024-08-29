# vibeshift

steal the vibe from photo(s) and apply it to your photo(s). this repo is just a list of comfyui workflows that will eventually go into an app to shift the aesthetic of any photo to match the style of shot taken from a polaroid or a leica or another camera. imagine a photo editor you could talk to...

![qschKrO8 jpg-medium](https://github.com/user-attachments/assets/5e9fe9c8-c29f-4bf2-9473-fc622eb53c76)

+ use a leica

![y52jNvd2 jpg-medium](https://github.com/user-attachments/assets/8819c937-7d44-4436-913d-8cd152465bf7)

or make the shot look like it was taken from a polaroid, flash

![uMN_Iccp jpg-medium](https://github.com/user-attachments/assets/f2162032-49ad-43a0-892b-394009e6096d)

## methods

1. ic-light (https://replicate.com/zsxkib/ic-light?prediction=05p9w3722xrgj0cgta29xcg428)

2. instructpix2pix 

3. ipadapter+canny (https://pastebin.com/ycQ4Dij1)

4. controlnet for sd-webui (https://github.com/Mikubill/sd-webui-controlnet)
    controlnet-sdxl-union(which has controlnet++)
    controlnet Tile(slight variations) https://huggingface.co/xinsir/controlnet-tile-sdxl-1.0

5. txt2img, with controlnet canny

6. Kolors

7. ipadapter+
    multiple image weightaverage + ipadapter
    composition transfer
    style transfer

8. restoredetail image filter

---

9. https://huggingface.co/bingbangboom/flux_mixReality


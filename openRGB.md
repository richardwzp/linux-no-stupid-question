# OpenRGB detection
### My hardware
- GPU: Sapphire Nitro+ 7000 series
- CPU: Ryzen 5 7000 series
- Mobo: MSI b650 S
- some Lian li fan

## Motherboard needs experimental build for detection
As of 7/3/2024, my MSI board cannot be detected unless using an experimental build (pipeline) of openRGB.
That's the `openrgb-git` package on AUR.

## Sapphire GPU needs to be toggled to external source
Assuming you have your RGB cable from the GPU plugged into the mobo, the mobo is detected, but the Sapphire gpu still doesn't change color, 
it might be because it's toggled to a trixx effect instead of external source.

You might need to somehow boot to windows and toggle that to `external source` with Sapphire's trixx software. I tried to do a VM gpu passthrough but failed, and had to dual boot instead.
I hope you have better luck.

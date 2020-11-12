# retropie2RGB

This is an RetroPie image for pi2jamma using the Raspberry PI 3b+ sofware.  It is a basic image without roms that should work "out-of-the-box" with minimal adjustments.  
The image is retropie with retropieRGB setup already completed. [Thank you ArcadeForge](https://github.com/arcadeforge/RetroPieRGB).
Themes and overlays are installed from [Phil's Doodles](https://github.com/lipebello/es-theme-retrorama).

## Hardware:
- pi2jamma: http://arcadeforge.net/
- Raspberry Pi 3b+: https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/?resellerType=home
- 32gb (or higher) microSD card: https://www.amazon.com/SanDisk-Ultra-microSDXC-Memory-Adapter/dp/B073JWXGNT/ref=sr_1_4?dchild=1&keywords=micro%2Bsd%2Bcard%2B32&qid=1605144503&sr=8-4&th=1

## Initial Setup-up:
1. Dowloand image
2. Insert SD card
3. Flash OS iamge to SD card: https://www.balena.io/etcher/

## RetroPie Settings:
https://retropie.org.uk/

## Troubleshooting:

**1.  Jamma Controls are not working**

F4 -> access the command line

sudo nano config.txt

```
# pi2jamma
# 1=Enabled
# 0=Disabled
pi2jamma=1   # make sure this line is set to 1 instead of 0
```

Credit:  https://www.facebook.com/groups/1649021265123737

# Fiber Optic LED Mod

Thanks to **PF#9918** on the Voron Discord for the original idea and design/process help along the way. 
Shout-out to **Logan#2225** on the Voron Discord for the idea to use transparent filament as a fiber optic cable.

#### This mod makes Raspberry Pi LEDs visible at front of machine.  This is particularly useful to ensure the Pi is finished its shutdown sequence prior to cutting power

https://user-images.githubusercontent.com/2540542/160301472-40bf80aa-4d31-4b27-8ec1-42aa3fb91417.mp4

## Part List
| STL File | Description | Image |
| --- | --- | --- |
| **Pi 3B Fiber Optic (Filament) Mount** | (Option 1) Fiber optic mount for Raspberry Pi 3B(+) & 4B - Use 1.75 mm [transparent TPU filament](https://www.amazon.ca/SainSmart-Flexible-Printing-Filament-Dimensional/dp/B00TI3JUWO) as your fiber optic cable (PLA does not work; PETG is not tested) | ![Pi 3B Fiber Optic (Filament) Mount](https://user-images.githubusercontent.com/2540542/160407918-8cb7a257-38bb-4d65-8b85-656e7d282615.jpg) |
| **Pi 3B Fiber Optic Mount Normal** | (Option 2) Fiber optic mount for Raspberry Pi 3B(+) & 4B; works with [this fiber optic cable from Digikey](https://www.digikey.ca/en/products/detail/industrial-fiber-optics/IF-C-E1000/356536) | ![Pi 3B Fiber Optic Mount Normal](https://user-images.githubusercontent.com/2540542/160301752-9d2c598a-7a3c-4dd7-bb3d-7071755d836e.jpg) |
| **Voron v2.4 Front Skirt Fiber (Filament) Insert** | (Option 1) Fiber holder that mounts in the front skirt of Voron v2: for TPU filament fiber| ![Voron v2 4 Front Skirt Fiber (Filament) Insert](https://user-images.githubusercontent.com/2540542/160408020-214cc23d-7884-45b4-b743-5efb22091f68.jpg) |
| **Voron v2.4 Front Skirt Fiber Optic Insert** | (Option 2) Fiber holder that mounts in the front skirt of Voron v2; for Digikey Fiber| ![Voron v2 4 Front Skirt Fiber Optic Insert](https://user-images.githubusercontent.com/2540542/160301779-df3b16f0-783c-4b96-9b97-3c9c18a715c4.jpg) |

## Installation Tips
* Use a flame to carefully melt the ends of the optical fiber/filament.  The surface should look smooth/glossy but not singed/burnt.  This will help the light couple into the fiber.
* On the output end of the fiber you can lightly sand the the tip with a fine sandpaper.  This will act as a diffuser to improve viewing angle.

## Help Wanted
* If you test with transparent PETG - please let me know if it works.
* If you test with a Pi 3B+ or Pi 4B - please confirm that everything fits.  The CAD looks compatible but I don't have those boards to test.

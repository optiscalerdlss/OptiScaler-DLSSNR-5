# OptiScaler DLSSNR 5

**OptiScaler DLSSNR 5** adds a DLSS 5 neural pass on top of OptiScaler. DLSS, FSR, XeSS.


<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/dd78cabb-5ace-45f7-8bbe-cfe86e93dd9f" />

## What's new in v0.2.0 (September 3, 2026)
- Official `v0.2.0` (September 3, 2026)
- Reversible proxy + Hybrid composed
- Frame hold, live exposure, model supersample to 2x
- NR on DLSS / FSR / XeSS. Native Vulkan crash fixes

<img width="960" height="2136" alt="image" src="https://github.com/user-attachments/assets/0eb4e84b-147d-4b54-a1af-5f875eabdec7" />

## How to use
1. Download v0.2.0.
2. Extract into the folder with the real game exe.
3. Run `setup_windows.bat`.
4. Drop `nvngx_dlssnr.dll`. Launch. Enable Neural Rendering in the overlay.

<img width="739" height="415" alt="image" src="https://github.com/user-attachments/assets/a40c0b6b-472b-40d0-955e-f63845da129e" />

## Key Features
- Reversible proxy
- Frame hold
- All upscalers
- Native Vulkan
- Keybind toggle

<img width="768" height="650" alt="image" src="https://github.com/user-attachments/assets/a4bd80c7-106b-451f-9767-07cd4f9d2215" />

## FAQ

**No NR?**
The model dll is not shipped. Notes in `files/nr/`.

**Replace flicker?**
Use Hybrid composed, not Replace.

## Requirements
Windows 10/11. Driver 616.56+. A game that already upscales.

## License
Opti notes - Copyright (C) 2026 optiscalerdlssnr

<img width="1300" height="372" alt="image" src="https://github.com/user-attachments/assets/c5d0d697-9711-49d3-9fea-928c2f0e1683" />

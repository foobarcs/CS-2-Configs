![couter strike banner](https://i.ibb.co/8Yq6F8T/cs2-banner-for-faceit.jpg)

### Specs
- 7800X3D  
- 4080 Super  
- 32GB 6000MHz  

### Main
- Pulsar Xlite V3 Size 3 (Supergrip) + 4K Dongle
- LGG Jupiter Pro V2 XSoft
- Wooting 60HE+
- ASUS ROG Swift PG27AQDP
- IEM: Dunu Vulkan / Mic: Shure MV7+
---

### CS2 In-game Video Settings

| Video Settings | Value |
| :---: | :-: |
| Brightness | 93% |
| Aspect Ratio | 4:3 |
| Resolution | 1440x1080 |
| Scaling Mode | Stretched |
| Display Mode | Fullscreen |

---

| Advanced Video Settings | Value |
| :---: | :-: |
| Boost Player Contrast | DISABLED |
| V-Sync | DISABLED |
| NVIDIA Reflex Low Latency | *-noreflex in launch option* |
| Maximum FPS In Game | 0 |
| Maximum FPS In Menus | 450 |
| Multisampling Anti-Aliasing Mode | 4X MSAA |
| Global Shadow Quality | LOW |
| Dynamic Shadows | ALL |
| Model / Texture Detail | LOW |
| Texture Filtering Mode | ANISOTROPIC 16X |
| Shader Detail | LOW |
| Particle Detail | LOW |
| Ambient Occlusion | MEDIUM |
| High Dynamic Range | QUALITY |
| FidelityFX Super Resolution | DISABLED (HIGHEST QUALITY) |

---

### NVIDIA Control Panel Settings

| NVIDIA Control Panel | Value |
| :---: | :-: |
| Low Latency Mode | ULTRA |
| Max Frame Rate | 450 *(set at 6% below monitor referesh rate)* |
| Power management mode | Prefer maximum performance |
| Text filtering - Anisotropic sample optimization | On|
| Text filtering - Quality | High performance |
| Text filtering - Trilinear optimization | On |
| Vertical sync | On |

--- 
[CS2 FPS BENCHMARK](https://steamcommunity.com/sharedfiles/filedetails/?id=3240880604)  

```
OS: Windows 11 Pro (KB 5041587)
NVIDIA version: 552.44  
Build ID: 16333861


[VProf] -- Performance report --
[VProf] Summary of 93067 frames.  (6560 frames excluded from analysis.)
[VProf] FPS: Avg=813.6, P1=283.5
[VProf] 
[VProf]                         All frames         Active frames   
[VProf]                           Avg    P99        N    Avg    P99
[VProf] ---------------------- ------ ------   ------ ------ ------
[VProf]             FrameTotal   1.23   3.53    93067   1.23   3.53
[VProf]       Client Rendering   0.80   1.20    93067   0.80   1.20
[VProf]         Frame Boundary   0.54   0.93    93067   0.54   0.93
[VProf]      Client Simulation   0.18   0.90    93067   0.18   0.90
[VProf]    ClientSimulateFrame   0.14   0.30    93067   0.14   0.30
[VProf]      Server Simulation   0.08   1.19     7313   0.97   1.51
[VProf]            Server Game   0.06   0.96     7313   0.78   1.35
[VProf]             Prediction   0.06   0.53    93067   0.06   0.53
[VProf]                    HUD   0.05   0.12    93067   0.05   0.12
[VProf]     ClientSimulateTick   0.03   0.57     7313   0.42   0.69
[VProf]           UserCommands   0.02   0.37     7313   0.31   0.61
[VProf]       Client_Animation   0.01   0.18     7313   0.16   0.25
[VProf]       Server Animation   0.01   0.14     7313   0.12   0.20
[VProf] Server Send Networking   0.01   0.12     7313   0.11   0.19
[VProf]                   NPCs   0.01   0.20     7313   0.11   0.30
[VProf] 
[VProf] VProfLite stopped.
```

---
### *High FPS not always equal smooth gameplay in CS2*
### *A stable frametime without significant frame spike and ideally the in-game 1% low should be close to your monitor’s refresh rate to achieve the buttery smooth gameplay experience in CS.*
<br>

| ![unstable frametime](https://i.ibb.co/sy0vdL1/unstable-frametime.png) | 
|:--:| 
| *fps_max 999, NVIDIA Reflex Enabled + Boost <br> Constant frametime spikes during FPS benchmark test* |

| ![stable frametime](https://i.ibb.co/J7gVBxR/stable-frametime.png) | 
|:--:| 
| *G-Sync: Enabled, VSync: Fast, NVCAP: 224 , Low Latency Mode: ON, fps_max 0, -noreflex in launch option <br> Barely any noticeable frametime spikes during FPS benchmark test* |  

| ![stable frametime with HAGS, Game Bar and Game Mode OFF](https://i.ibb.co/SJTvbB1/HAGS-GAMEMODE-GAMEBAR-OFF.png) | 
|:--:| 
| *G-Sync: Enabled, VSync: Fast, NVCAP: 224 , Low Latency Mode: ON, fps_max 0, -noreflex in launch option <br> HAGS: Off and Game Mode: Off can delivered the highest 1% and 0.1%* |  




#### To find out the best settings for your PC specs. Download [CapFrameX](https://www.capframex.com/download) run the FPS Benchmark Map and capture the frametime.
#### Additonal test can be done on Valve MM, Faceit or I personally find [WarmUp Server](https://www.warmupserver.net) are the most optimised server to test frametime or the responsiveness and smoothness of CS2 after changing diffrent settings.
#### *A benchmark test alongside with analysis tools can helps eliminate the placebo effect.*
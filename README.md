# FastFlags List

## Info
<font color='red'>**143 Currently Listed**</font>  
Textures not working right now. Because Roblox removed "FFlagMSRefactor5"

## List Navigation
• [Lightning Technologies](#lightning-technologies)

• Rendering  
• Graphics  
• UI  
• Textures  
• Physics  
• Other FFlags

══════⊹⊱≼≽⊰⊹══════

# Lightning Technologies

### Voxel Lighting (Phase 1)
```
{
    "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```

### Shadowmap Lighting (Phase 2)
```
{
    "FFlagDebugForceFutureIsBrightPhase2": "True"
}
```

### Future Lighting (Phase 3)
```
{
    "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

# Rendering API

### MacOS Only
```
{
    "FFlagDebugGraphicsPreferMetal": "True"
}
```

### Vulkan
```
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferVulkan": "True"
}
```

### OpenGL
```
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferOpenGL": "True"
}
```

### Direct X 10
```
{
    "FFlagDebugGraphicsPreferD3D11FL10": "True"
}
```

### Direct X 11
```
{
    "FFlagDebugGraphicsPreferD3D11": "True"
}
```

# Graphical Settings & More

### Draws a circle under avatars
```
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
```

### HyperThreading
```
{
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True"
}
```

### Maximum Threads
```
{
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```

### Minimum Threads
```
{
    "FIntTaskSchedulerThreadMin": "3"
}
```

### Smoother Terrain
```
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

### Graphics Quality Level
```
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Quallity Terrain Textures
<small>4 for less quality 16, 32, 64 for higher quality</small>
```
{
    "FIntTerrainArraySliceSize": "4"
}
```

### Disable Shadows
```
{
    "FIntRenderShadowIntensity": "0"
}
```

### Preserve rendering quality with display setting
```
{
    "DFFlagDisableDPIScale": "True"
}
```

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
<small>Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider</small>
```
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```
<center>
### FRM Levels
</center>

```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

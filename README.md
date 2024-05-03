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

### FRM Levels
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

### 21 Graphics Quality Slider
```
{
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True"
}
```

### Low Render Distance
[FRM](#frm-levels)
```
{
    "DFIntDebugRestrictGCDistance": "1"
}
```

### Disable Wind
```
{
    "FFlagGlobalWindRendering": "False",
    "FFlagGlobalWindActivated": "False"
}
```

### Limits Light Updates
```
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```

### Disables fade in and fade out animation every light update
```
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```

### Makes avatars shiny
<small>[everything goes black on <3] [DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3</small>
```
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```

### Disable PostFX
```
{
    "FFlagDisablePostFx": "True"
}
```

### Pause Voxelizer/Disable Baked Shadows
```
{
    "DFFlagDebugPauseVoxelizer": "True"
}
```

### Gray Sky
<small>Only applies to games with the default skybox</small>

### Disable Player Shadows
```
{
    "FIntRenderShadowIntensity": "0"
}
```

### Force LOD on Meshes
```
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```

### Lighting Attenuation
```
{
    "FFlagNewLightAttenuation": "True"
}
```

### Enable GPULightCulling
<small>Combine with Lighting Attenuation for better vision</small>
```
{
    "FFlagFastGPULightCulling3": "True"
}
```

### Frame Buffer
<small>Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag</small>
```
{
    "DFIntMaxFrameBufferSize": "4"
}
```

### High Quality Textures
<small>[1-3]</small>
```
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```

### Lower Quality Textures
<small>[1-3]</small>
```
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```

### No avatar textures
```
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```

### Remove Grass
``` 
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntRenderGrassHeightScaler": "0"
}
```

### Force MSAA
<small>[0, 1, 2, 4, 8]</small>
```
{
    "FIntDebugForceMSAASamples": "4"
}
```

### ShadowMap Bias
<small>[Future & ShadowMap]</small>
```
{
    "FIntRenderShadowmapBias": "75"
}
```

### Enables Network Debug Tracker menu
<small>(aka Can be used as ESP)</small>

<small>Instructions: CTRL+F8</small>
```
{
    "DFFlagDebugEnableInterpolationVisualizer": "True"
}
```

### Humanoid Outline
<small>Draws an outline around every part and every humanoid</small>
```
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```

### FFlag above but more complex
<small>Draws an outline around every body part</small>
```
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```

### Buggy ZPlane Camera
<small>aka Can be used as XRAY</small>
```
{
    "FIntCameraFarZPlane": "1"
}
```

### Xray
<small>Some camera positions, will make textures transparent</small>
```
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

# User Interface

### Home Siderbar Text
```
{
    "FFlagEnableNavBarLabels3": "True"
}
```

### Revert New "Builder" Font
```
{
    "FFlagEnableNewFontNameMappingABTest2": "False"
}
```

### Revert spacing on errors
```
{
    "FFlagErrorPromptResizesHeight": "False"
}
```

### GUI Hiding Toggles
```
{
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True"
}
```

### Darker Dark Theme
```
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True"
}
```

### Subscriptions Page
```
{
    "FFlagLuaAppDevSubsEnabled": "True"
}
```

### No Transparency V4 Menu (2023)
```
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```

### Revert Old Report Menu
```
{
    "FStringReportAbuseMenuRoactForcedUserIds": "null",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableReportAbuseMenuRoact2": "False",
    "FFlagEnableReportAbuseMenuLayerOnV3": "False"
}
```

### Custom MicroProfile Scale
```
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```

### Hides gui
```
{
    "FFlagDebugAdornsDisabled":  "True"
}
```

### Dont Render UI
```
{
    "FFlagDebugDontRenderUI": "True"
}
```

### Dont Render Screen GUIs
```
{
    "FFlagDebugDontRenderScreenGui": "True"
}
```

### Enable Audio Controller
```
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```

### Disable Autocomplete
```
{
    "FFlagEnableCommandAutocomplete": "False"
}
```

### Chrome UI TopBar
```
{
    "FFlagEnableInGameMenuChrome": "True",
    "FFlagEnableReportAbuseMenuRoactABTest2": "True",
    "FFlagChromeBetaFeature": "True",
    "FFlagEnableInGameMenuChromeABTest2": "True"
}
```

### Pin Chat on Chrome UI
```
{ "FFlagEnableChromePinnedChat":  "True" }
```

### Chrome UI Topbar Removal
```
{
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False"
}
```

### Disable Bubble Chat
```
{
    "FFlagEnableBubbleChatFromChatService":  "False"
}
```

### Disable Selfview
```
{
    "FFlagCoreGuiTypeSelfViewPresent":  "False"
}
```

### Remove VC Beta Badge
```
{
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagEnableBetaBadgeLearnMore": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```

### Hide guis
<small>Instructions: Replace "ID" with any group ID that you are in.</small>
| Key combination | Action |
| --------------- | ------ |
| Ctrl + Shift + B | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc) |
| Ctrl + Shift + C | Toggles game-defined ScreenGuis |
| Ctrl + Shift + G | Toggles Roblox CoreGuis |
| Ctrl + Shift + N | Toggles player names, and other BillboardGuis that show up above a player |
```
{
    "DFIntCanHideGuiGroupId": "ID"
}
```

### Disable Fullscreen Title Bar
```
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```

### Set Custom Font Size
```
{
    "FIntFontSizePadding": "1"
}
```

### Set Custom Kick Message Lenght
```
{
    "FIntMaxKickMessageLength": "1"
}
```

# Textures

### Fix Textures
```
{
          "FFlagMSRefactor5": "False"
}
```

### No Textures
```
{
          "FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
          "FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
          "FStringTerrainMaterialTable2022": "",
          "FStringTerrainMaterialTablePre2022": "",
          "FFlagMSRefactor5": "False"
}
```

### Trollface Textures
```
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
```

### Black Textures
```
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FFlagMSRefactor5": "False"
}
```

### White Textures
```
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FFlagMSRefactor5" :"False"
}
```

### Minecraft Textures
```
{
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://9873266399\",\"rbxassetid://9438410239\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://11545552824\",\"rbxassetid://11545440462\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://9924770651\",\"rbxassetid://9924770538\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://9919719550\",\"rbxassetid://9438453972\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://9924775913\",\"rbxassetid://9924775826\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://9920485426\",\"rbxassetid://9438453972\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://10237721036\",\"rbxassetid://9438453972\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://9920517963\",\"rbxassetid://9438453972\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://9920518995\",\"rbxassetid://9438453972\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://9920550720\",\"rbxassetid://9438453972\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://11546360009\",\"rbxassetid://11545533676\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://9920556429\",\"rbxassetid://9438453972\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://9920561624\",\"rbxassetid://9438453972\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://9873292869\",\"rbxassetid://9438453972\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://11546526557\",\"rbxassetid://11546431794\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://9920578676\",\"rbxassetid://9438453972\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://11546539560\",\"rbxassetid://11546440685\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://9920581197\",\"rbxassetid://9438453972\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://9868015012\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://11546570730\",\"rbxassetid://11546456858\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://11545623165\",\"rbxassetid://11545476330\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://9920590478\",\"rbxassetid://9438453972\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://11546588111\",\"rbxassetid://11546468464\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://9920596353\",\"rbxassetid://9438453972\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://11536062048\",\"rbxassetid://11108916253\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
```

# Physics

### N/A
```
{
    "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
    "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
    "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
    "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
}
```

### Crash Roblox
```
{
    "DFIntTimestepArbiterThresholdCFLThou": "0"
}
```

### Stuttery Animation Fix
```
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```

### Remap R6 to R15 Rigs/Weird Movement
```
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
```

### Weird Leg Movement
```
{
    "DFFlagAnimatorPostProcessIK": "True"
}
```

### Adjust Hip Height Clamps
<small>https://www.roblox.com/bundles/63/Mage-Animation-Package</small>
```
{
    "DFIntHipHeightClamp": "-48"
}
```

### Random High Jumps
<small>Video will be added soon</small>
```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

### Possible Super Jump
```
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```

### Drunk
```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

### No Animations
<small>Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client</small>
```
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```

### Stick unanchored parts to you
<small>- = up, + = down</small>
```
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

### Max Raycast Distance
<small>Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3</small>
```
{
    "DFIntRaycastMaxDistance": "3"
}
```

### Change DataSender Rate
<small>aka dos not let you load games</small>
```
{
    "DFIntDataSenderRate": "-1"
}
```

### Disable Touch Events
```
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```

### Fake Lag
```
{
    "DFIntS2PhysicsSenderRate": "1"
}
```

### Invisible 1
<small>Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.</small>
```
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```

### Invisible 2
<small>Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable.</small>
```
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```

### Invisible 3 (BEST INVISIBLE)
<small>Restricts the client from sending any physics-related information. This means other people can topple you over.</small>
```
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```

### Clientsided Invisible
```
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1",
}
```

### Warp & Slowmotion
```
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```
```
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```

### Noclip
<small>Adjust the value so you don't fall through the ground</small>
```
{
        "DFFlagAssemblyExtentsExpansionStudHundredth": "-50"
}
```

### Hip Height
<small>Very controllable bounce, only works with negative values, 0 allows you to hover</small>
```
{
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```

### Wallglide
```
{
    "DFIntUnstickForceAttackInTenths": "-4"
}
```

# Other FFlags

### Disable In-game Advertisements
```
{
    "FFlagAdServiceEnabled": "False"
}
```

### Disable Telemetry
```
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True"
}
```

### Adjust Scroll Speed
```
{
    "FIntScrollWheelDeltaAmount": "140"
}
```

### Surf the web inside of Roblox
<small>Click the Beta badge or the 13+ badge to open the webview browser.</small>
```
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```

### Sounds use physical velocity and become distorted
<small><2017</small>
```
{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
```

### Shows the state of a flag
```
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```
<small>e.g</small>
```
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```

### MTU
```
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```

### Increase Ping
```
{
    "DFIntDataSenderMaxBandwidthBps": "150"
}
```

### No Internet Disconnect
<small>You will still be kicked but the message wont show.</small>
```
{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
```

### Quick Game Launch
<small>BUGGY</small>
```
{
    "FFlagEnableQuickGameLaunch": "True"
}
```

### Allows you to change voice chat distance
<small>default: [Min 7 Max 80]</small>
```
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```

### Disable In-Game Purchases
```
{
    "DFFlagOrder66": "True"
}
```

### Disable Chat
```
{
    "FFlagDebugForceChatDisabled": "True"
}
```

### Limit audios that are being played
```
{
    "DFIntMaxLoadableAudioChannelCount": "1"
}
```

### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```
{
    "FFlagDebugHumanoidRendering": "True"
}
```

### Custom Disconnect Message
```
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```

### Display FPS
```
{
    "FFlagDebugDisplayFPS": "True"
}
```

### Verified Badge
<small>Clientsided</small>
```
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```

### Verified Badge on everyone
<small>Clientsided</small>
```
{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
```

### Applies cool colors to stuff
```
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
```

### Show Outlined Chunks
```
{
    "FFlagDebugLightGridShowChunks": "True"
}
```

### Show Outlined Chunks that are being interacted
```
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
```

### Remove Disconnect Blur/Loading Blur
```
{
    "FIntRobloxGuiBlurIntensity": "0"
}
```

### Disable Dynamic Heads Animations
<small>https://roblox.fandom.com/wiki/Dynamic_Head</small>
```
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```

### Fail Safe Humanoid
<small>gray avatars</small>
```
{
    "FFlagFailsafeHumanoid_3": "True"
}
```

### Automatically unmutes your mic on join (VC)
```
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```

### Overlay that shows what you type
```
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
```

### Ammount of lines to show at once for above
```
{
    "DFIntTextBoxServiceHistorySize": "1"
}
```

### Opt-Put Experience Language
<small>Removes the Experience Language option in settings</small>
```
{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```

### Disable New Chat Translation Settings
```
{
    "FFlagChatTranslationSettingEnabled3 ": "False"
}
```

### Lets you change the zoom out limit
<small>Only applies to games that has not changed the default zoom limit</smalL>
```
{
    "FIntCameraMaxZoomDistance": "9999"
}
```

### Limits number of animations being played
```
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```

### Prevents Remote Events from running
```
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```

### Mess with voice chat volume
<small>default 1000</small>
```
{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
```

### Removes the head roll limit for face tracking
<small>Removes the head roll limit for face tracking</small>
```
{
    "DFIntAvatarFaceChatHeadRollLimitDegrees": "360"
}
```

### VR Controller transparency
```
{
    "FIntVRTouchControllerTransparency": "0"
}
```

### No sounds
```
{
    "FFlagDebugRomarkMockingAudioDevices": "True"
}
```

### Exclusive Fullscreen
```
{
    "FFlagHandleAltEnterFullscreenManually": "False"
}
```

### Logs stuff in dev console
```
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```

### Self Explanatory 1
```
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
```

### Self Explanatory 2
```
{
    "DFFlagDebugAudioLogging": "True"
}
```

### Duplicate of Above
```
{
    "DFFlagDebugAudioLogging2": "True"
}
```

### Self Explanatory 3
```
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```

### Self Explanatory 4
<small>Disable Drag Detectors</small>
```
{
    "FFlagDragDetectors1": "False"
}
```

### Self Explanatory 5
<small>Disabe CTM Climbin</small>
```
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```

### Self Explanatory 6
<small>Disabe Feedback Button in ESC</small>
```
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```

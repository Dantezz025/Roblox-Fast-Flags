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

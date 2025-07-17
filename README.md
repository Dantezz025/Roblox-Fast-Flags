<h1 align="center">Fast Flag List</h2>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Dantezz025/Roblox-Fast-Flags/blob/main/LICENSE) [![Terms Of Use](https://img.shields.io/badge/Of%20Use-brightgreen?label=Terms)](https://github.com/Dantezz025/Roblox-Fast-Flags/blob/main/TERMS.md)

<h1 align="center">Support Me</h2>
https://github.com/Dantezz025/Roblox-Fast-Flags/blob/main/.github/FUNDING.yml

<h1 align="center">Contact Me</h2>

You can reach me via telegram: dantezz95

Want closed community fast flags? Dm me on discord or telegram for more info.

If you have any fflag related questions join to the linked dc server and go to the fflag help forum.

<h1 align="center">Info</h2>

- 149 currently listed

- Last update on 16.02.2025 | If there's any outdated fflags, please open pull request/issues and let me know what's not working

---

> [!WARNING]
> #### USE IT ON YOUR OWN RISK
> **Some Fast Flags Can Be Banable In Certain Games**

---

# Bloxstrap How to Use:
1. Open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).
2. Navigate to Fast Flags >> Fast Flags Editor >> Import Json.
3. Paste in the JSON.
4. Save and your good to go!

# Normal Roblox Bootstrapper How to Use:
1. Navigate to your Roblox Installation directory. Typically found at %localappdata%\Roblox\Versions\ for Windows or C:\Program Files (x86)\Roblox\Versions.
2. Identify the folder version-xxxxxxxxxxxxxxxx containing RobloxPlayerBeta.exe You can do this for Roblox Studio too.
3. Download ClientSettings Folder and put it in folder you opened before
4. Save and your good to go!

## List Navigation
• [Lightning Technologies](#lightning-technologies)

• [Rendering](#rendering-api)

• [Graphics](#graphical-settings--more)

• [UI](#user-interface)  

• [Physics](#physics)  

• [Other FFlags](#other-fflags)

• [FFLAG Combinations](#fast-flag-combinations)

══════⊹⊱≼≽⊰⊹══════

<h1 align="center">Lightning Technologies</h2>

### Voxel Lighting (Phase 1)
```json
{
    "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```

### Shadowmap Lighting (Phase 2)
```json
{
    "FFlagDebugForceFutureIsBrightPhase2": "True"
}
```

### Future Lighting (Phase 3)
```json
{
    "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

<h1 align="center">Rendering API</h2>

### MacOS Only
```json
{
    "FFlagDebugGraphicsPreferMetal": "True"
}
```

### Vulkan
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferVulkan": "True"
}
```

### OpenGL
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferOpenGL": "True"
}
```

### Direct X 10
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "True"
}
```

### Direct X 11
```json
{
    "FFlagDebugGraphicsPreferD3D11": "True"
}
```

<h1 align="center">Graphical Settings & More</h2>

### Draws a circle under avatars
```json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
```

### HyperThreading
```json
{
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True"
}
```

### Maximum Threads
```json
{
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```

### Minimum Threads
```json
{
    "FIntTaskSchedulerThreadMin": "3"
}
```

### Smoother Terrain
```json
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

### Graphics Quality Level
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
    "FIntTerrainArraySliceSize": "4"
}
```

### Disable Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```

### Preserve rendering quality with display setting
```json
{
    "DFFlagDisableDPIScale": "True"
}
```

### Low Graphics - High Render Distance
```json
{
"DFFlagDebugRenderForceTechnologyVoxel": true,
"DFIntDebugFRMQualityLevelOverride": 1,
"FIntRenderShadowIntensity": 0
}
```

### Disable Wind
```json
{
    "FFlagGlobalWindRendering": "False",
    "FFlagGlobalWindActivated": "False"
}
```

### Limits Light Updates
```json
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```

### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```

### Makes avatars shiny
###### [everything goes black on <3] [DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```

### Disable PostFX
```json
{
    "FFlagDisablePostFx": "True"
}
```

### Pause Voxelizer/Disable Baked Shadows
```json
{
    "DFFlagDebugPauseVoxelizer": "True"
}
```

### Gray Sky
###### Only applies to games with the default skybox
```json
{
    "FFlagDebugSkyGray": "True"
}
```

### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```

### Force LOD on Meshes
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```

### Lighting Attenuation
```json
{
    "FFlagNewLightAttenuation": "True"
}
```

### Enable GPULightCulling
###### Combine with Lighting Attenuation for better vision
```json
{
    "FFlagFastGPULightCulling3": "True"
}
```

### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{
    "DFIntMaxFrameBufferSize": "4"
}
```

### High Quality Textures
###### [1-3]
```json
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```

### Lower Quality Textures
###### [1-3]
```json
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```

### No avatar textures
```json
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```

### Remove Grass
```json
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntRenderGrassHeightScaler": "0"
}
```

### Force MSAA
###### [0, 1, 2, 4, 8, 16]
```json
{
    "FIntDebugForceMSAASamples": "4"
}
```

### ShadowMap Bias
###### [Future & ShadowMap]
```json
{
    "FIntRenderShadowmapBias": "75"
}
```

### Humanoid Outline
###### Draws an outline around every part and every humanoid
```json
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```

### FFlag above but more complex
###### Draws an outline around every body part
```json
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```

### Buggy ZPlane Camera <sup>a.k.a xray</sup>
```json
{
    "FIntCameraFarZPlane": "1"
}
```

### Xray
###### Some camera positions, will make textures transparent
```json
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

<h1 align="center">User Interface</h2>

### Home Siderbar Text
```json
{
    "FFlagEnableNavBarLabels3": "True"
}
```

### Revert New "Builder" Font
```json
{
    "FFlagEnableNewFontNameMappingABTest2": "False"
}
```

### Revert spacing on errors
```json
{
    "FFlagErrorPromptResizesHeight": "False"
}
```

### GUI Hiding Toggles
```json
{
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True"
}
```

### Darker Dark Theme
```json
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True"
}
```

### Subscriptions Page
```json
{
    "FFlagLuaAppDevSubsEnabled": "True"
}
```

### No Transparency V4 Menu (2023)
```json
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```

### Revert Old Report Menu
```json
{
    "FStringReportAbuseMenuRoactForcedUserIds": "null",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableReportAbuseMenuRoact2": "False",
    "FFlagEnableReportAbuseMenuLayerOnV3": "False"
}
```

### Custom MicroProfile Scale
```json
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```

### Hides gui
```json
{
    "FFlagDebugAdornsDisabled":  "True"
}
```

### Dont Render UI
```json
{
    "FFlagDebugDontRenderUI": "True"
}
```

### Dont Render Screen GUIs
```json
{
    "FFlagDebugDontRenderScreenGui": "True"
}
```

### Enable Audio Controller
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```

### Disable Autocomplete
```json
{
    "FFlagEnableCommandAutocomplete": "False"
}
```

### Chrome UI TopBar
```json
{
    "FFlagEnableInGameMenuChrome": "True",
    "FFlagEnableReportAbuseMenuRoactABTest2": "True",
    "FFlagChromeBetaFeature": "True",
    "FFlagEnableInGameMenuChromeABTest2": "True"
}
```

### Pin Chat on Chrome UI
```json
{ "FFlagEnableChromePinnedChat":  "True" }
```

### Chrome UI Topbar Removal
```json
{
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False"
}
```

### Disable Bubble Chat
```json
{
    "FFlagEnableBubbleChatFromChatService":  "False"
}
```

### Disable Selfview
```json
{
    "FFlagCoreGuiTypeSelfViewPresent":  "False"
}
```

### Remove VC Beta Badge
```json
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
```json
{
    "DFIntCanHideGuiGroupId": "ID"
}
```

### Disable Fullscreen Title Bar
```json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```

### Set Custom Font Size
```json
{
    "FIntFontSizePadding": "1"
}
```

### Set Custom Kick Message Lenght
```json
{
    "FIntMaxKickMessageLength": "1"
}
```

<h1 align="center">Physics</h2>

### Fps Unlocker (NEW)
```json
{
    "DFIntTaskSchedulerTargetFps": "29383" ,
    "FFlagGameBasicSettingsFramerateCap5": "False" ,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False"
}
```

### N/A
```json
{
    "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
    "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
    "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
    "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
}
```

### Crash Roblox
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "0"
}
```

### Stuttery Animation Fix
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```

### Remap R6 to R15 Rigs/Weird Movement
```json
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
```

### Weird Leg Movement
```json
{
    "DFFlagAnimatorPostProcessIK": "True"
}
```

### Random High Jumps
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

### Possible Super Jump
```json
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```

### Desync FFlag
```json
{
    "DFFlagPhysicsSkipNonRealTimeHumanoidForceCalc2": "False",
    "DFIntS2PhysicsSenderRate": "3",
    "DFIntTaskSchedulerTargetFps": 5588562,
    "FFlagGameBasicSettingsFramerateCap5": "False" ,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False"
}
```

### Ultimate Desync
```json
{
    "DFIntS2PhysicsSenderRate": "1", 
    "FIntPGSAngularDampingPermilPersecond": "0" 
}
```

### Tool Desyncs
```json
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
```

### Increase walking/run speed
###### Working in some games, one of them "Phantom Forces". Fast Flag just making you slightly faster
```json
{
    "DFIntDebugSimPhysicsSteppingMethodOverride": "10000000"
}
```

### Network Ownership
###### Better network ownership of parts. This might get you banned in some games with anticheats (Limbobbia)
```json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
```

### Freeze
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "0"
}
```

### Drunk
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

### No Animations
###### Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```

### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```

### Change DataSender Rate <sup>a.k.a does not let you load games</sup>
```json
{
    "DFIntDataSenderRate": "-1"
}
```

### Disable Touch Events
```json
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```

### Fake Lag
```json
{
    "DFIntS2PhysicsSenderRate": "1"
}
```

### Invisible 1
###### Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.
```json
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```

### Invisible 2
###### Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable.
```json
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```

### Invisible 3 (BEST INVISIBLE)
###### Restricts the client from sending any physics-related information. This means other people can topple you over.
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFFlagDebugSimPrimalFeedback": "True",
    "DFIntDebugSimPrimalStiffnessMax": "0",
    "DFIntDebugSimPrimalStiffnessMin": "0",
    "DFIntMaximumFreefallMoveTimeInTenths": "1000"
}
```

### Clientsided Invisible
```json
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1"
}
```

### Warp & Slowmotion
```json
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```
```json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```

### Noclip (Probably Best One)
###### Adjust the value so you don't fall through the ground
```json
{
        "DFFlagAssemblyExtentsExpansionStudHundredth": "-50"
}
```

### Noclip 2 
```json
{
    "DFIntSimBroadPhasePairCountMax": "50"
}
```

### Noclip 3
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalStiffness": "0"
}
```

### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```

<h1 align="center">Other FFlags</h2>

### Anti No Wifi Kick
```json
{
    "DFFlagDebugDisableTimeoutDisconnect" : "True"
}
```

### Custom Disconnect Message
```json
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```

### Voice Chat Distance
###### default: [Min 7 Max 80]
```json
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```

### Disable In-game Advertisements
```json
{
    "FFlagAdServiceEnabled": "False"
}
```

### Disable Telemetry
```json
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
```json
{
    "FIntScrollWheelDeltaAmount": "140"
}
```

### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```

### Sounds use physical velocity and become distorted
###### 2017
```json
{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
```

### Shows the state of a flag
```json
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```

###### e.g
```json
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```

### MTU
###### [Might Improve Ping]
```json
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```

### Increase Ping
```json
{
    "DFIntDataSenderMaxBandwidthBps": "150"
}
```

### No Internet Disconnect
###### You will still be kicked but the message wont show.
```json
{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
```

### Quick Game Launch
###### BUGGY
```json
{
    "FFlagEnableQuickGameLaunch": "True"
}
```

### Allows you to change voice chat distance
###### default: [Min 7 Max 80]
```json
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```

### Disable In-Game Purchases
```json
{
    "DFFlagOrder66": "True"
}
```

### Disable Chat
```json
{
    "FFlagDebugForceChatDisabled": "True"
}
```

### Limit audios that are being played
```json
{
    "DFIntMaxLoadableAudioChannelCount": "1"
}
```

### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
    "FFlagDebugHumanoidRendering": "True"
}
```

### Custom Disconnect Message
```json
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```

### Display FPS
```json
{
    "FFlagDebugDisplayFPS": "True"
}
```

### Verified Badge
###### Clientsided
```json
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```

### Verified Badge on everyone
###### Clientsided
```json
{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
```

### Applies cool colors to stuff
```json
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
```

### Show Outlined Chunks
```json
{
    "FFlagDebugLightGridShowChunks": "True"
}
```

### Show Outlined Chunks that are being interacted
```json
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
```

### Remove Disconnect Blur/Loading Blur
```json
{
    "FIntRobloxGuiBlurIntensity": "0"
}
```

### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```

### Automatically unmutes your mic on join (VC)
```json
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```

### Overlay that shows what you type
```json
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
```

### Ammount of lines to show at once for above
```json
{
    "DFIntTextBoxServiceHistorySize": "1"
}
```

### Opt-Put Experience Language
###### Removes the Experience Language option in settings
```json
{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```

### Disable New Chat Translation Settings
```json
{
    "FFlagChatTranslationSettingEnabled3 ": "False"
}
```

### Lets you change the zoom out limit
###### Only applies to games that has not changed the default zoom limit
```json
{
    "FIntCameraMaxZoomDistance": "9999"
}
```

### Limits number of animations being played
```json
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```

### Prevents Remote Events from running
```json
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```

### Mess with voice chat volume
###### default 1000
```json
{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
```

### Removes the head roll limit for face tracking
###### Removes the head roll limit for face tracking
```json
{
    "DFIntAvatarFaceChatHeadRollLimitDegrees": "360"
}
```

### VR Controller transparency
```json
{
    "FIntVRTouchControllerTransparency": "0"
}
```

### No sounds
```json
{
    "FFlagDebugRomarkMockingAudioDevices": "True"
}
```

### Exclusive Fullscreen
```json
{
    "FFlagHandleAltEnterFullscreenManually": "False"
}
```

### Logs stuff in dev console
```json
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```

### Don't touch walls!!!
```json
{
    "DFIntDebugSimPrimalNewtonIts": "-2147483647",
    "DFIntDebugSimPrimalToleranceInv": "-2147483647",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
```

### Self Explanatory 1
```json
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
```

### Self Explanatory 2
```json
{
    "DFFlagDebugAudioLogging": "True"
}
```

### Duplicate of Above
```json
{
    "DFFlagDebugAudioLogging2": "True"
}
```

### Self Explanatory 3
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```

### Self Explanatory 4
###### Disable Drag Detectors
```json
{
    "FFlagDragDetectors1": "False"
}
```

### Self Explanatory 5
###### Disabe CTM Climbin
```json
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```

### Self Explanatory 6
###### Disabe Feedback Button in ESC
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```

<h1 align="center">Fast Flag Combinations</h2>

### Lower Ping
```json
{
"DFIntConnectionMTUSize": 900,
"FIntRakNetResendBufferArrayLength": "128",
"FFlagOptimizeNetwork": "True",
"FFlagOptimizeNetworkRouting": "True",
"FFlagOptimizeNetworkTransport": "True",
"FFlagOptimizeServerTickRate": "True",
"DFIntServerPhysicsUpdateRate": "60",
"DFIntServerTickRate": "60",
"DFIntRakNetResendRttMultiple": "1",
"DFIntRaknetBandwidthPingSendEveryXSeconds": "1",
"DFIntOptimizePingThreshold": "50",
"DFIntPlayerNetworkUpdateQueueSize": "20",
"DFIntPlayerNetworkUpdateRate": "60",
"DFIntNetworkPrediction": "120",
"DFIntNetworkLatencyTolerance": "1",
"DFIntMinimalNetworkPrediction": "0.1"
}
```

### Boost FPS (Comfort To Play)
```json
{
"DFIntCSGLevelOfDetailSwitchingDistance": 250,
"DFIntCSGLevelOfDetailSwitchingDistanceL12": 500,
"DFIntCSGLevelOfDetailSwitchingDistanceL23": 750,
"DFIntCSGLevelOfDetailSwitchingDistanceL34": 1000,
"DFIntTextureQualityOverride": 1,
"FFlagDisablePostFx": true
}
```

### Boost FPS
```json
{
"FFlagDebugDisableTelemetryEphemeralCounter": true,
"FFlagDebugDisableTelemetryEphemeralStat": true,
"FFlagDebugDisableTelemetryEventIngest": true,
"FFlagDebugDisableTelemetryPoint": true,
"FFlagDebugDisableTelemetryV2Counter": true,
"FFlagDebugDisableTelemetryV2Event": true,
"FFlagDebugDisableTelemetryV2Stat": true
}
```

### Absoulutely kills your game graphics
```json
{
    "FFlagDisablePostFx": "True",
    "FIntDebugTextureManagerSkipMips": "-1",
    "DFIntTextureCompositorActiveJobs": "0",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "DFIntTextureQualityOverride": "1"
}
```

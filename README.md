<h1 align="center">Fast Flag List</h2>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Dantezz025/Roblox-Fast-Flags/blob/main/LICENSE) [![Terms Of Use](https://img.shields.io/badge/Of%20Use-brightgreen?label=Terms)](https://github.com/Dantezz025/Roblox-Fast-Flags/blob/main/TERMS.md)

<h1 align="center">Contact Me</h2>

You can reach me via telegram: dantezz95

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

<h1 align="center">Rendering API</h2>

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

<h1 align="center">Graphical Settings & More</h2>

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
###### 4 for less quality 16, 32, 64 for higher quality
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

### Low Graphics - High Render Distance
```
{
"DFFlagDebugRenderForceTechnologyVoxel": true,
"DFIntDebugFRMQualityLevelOverride": 1,
"FIntRenderShadowIntensity": 0
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
###### [everything goes black on <3] [DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3
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
###### Only applies to games with the default skybox
```
{
    "FFlagDebugSkyGray": "True"
}
```

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
###### Combine with Lighting Attenuation for better vision
```
{
    "FFlagFastGPULightCulling3": "True"
}
```

### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```
{
    "DFIntMaxFrameBufferSize": "4"
}
```

### High Quality Textures
###### [1-3]
```
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```

### Lower Quality Textures
###### [1-3]
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
###### [0, 1, 2, 4, 8, 16]
```
{
    "FIntDebugForceMSAASamples": "4"
}
```

### ShadowMap Bias
###### [Future & ShadowMap]
```
{
    "FIntRenderShadowmapBias": "75"
}
```

### Humanoid Outline
###### Draws an outline around every part and every humanoid
```
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```

### FFlag above but more complex
###### Draws an outline around every body part
```
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```

### Buggy ZPlane Camera <sup>a.k.a xray</sup>
```
{
    "FIntCameraFarZPlane": "1"
}
```

### Xray
###### Some camera positions, will make textures transparent
```
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

<h1 align="center">User Interface</h2>

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

<h1 align="center">Physics</h2>

### Fps Unlocker (NEW)
```
{
    "DFIntTaskSchedulerTargetFps": "29383" ,
    "FFlagGameBasicSettingsFramerateCap5": "False" ,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False"
}
```

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
###### https://www.roblox.com/bundles/63/Mage-Animation-Package
```
{
    "DFIntHipHeightClamp": "-48"
}
```

### Random High Jumps
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

### Desync FFlag
```
{
    "DFFlagPhysicsSkipNonRealTimeHumanoidForceCalc2": "False",
    "DFIntS2PhysicsSenderRate": "3",
    "DFIntTaskSchedulerTargetFps": 5588562,
    "FFlagGameBasicSettingsFramerateCap5": "False" ,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False"
}
```

### Ultimate Desync
```
{
    "DFIntS2PhysicsSenderRate": "1", 
    "FIntPGSAngularDampingPermilPersecond": "0" 
}
```

### Tool Desyncs
```
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
```

### Increase walking/run speed
###### Working in some games, one of them "Phantom Forces". Fast Flag just making you slightly faster
```
{
    "DFIntDebugSimPhysicsSteppingMethodOverride": "10000000"
}
```

### Network Ownership
###### Better network ownership of parts. This might get you banned in some games with anticheats (Limbobbia)
```
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
```

### Freeze
```
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "0"
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
###### Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client
```
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```

### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```
{
    "DFIntRaycastMaxDistance": "3"
}
```

### Change DataSender Rate <sup>a.k.a does not let you load games</sup>
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
###### Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.
```
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```

### Invisible 2
###### Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable.
```
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```

### Invisible 3 (BEST INVISIBLE)
###### Restricts the client from sending any physics-related information. This means other people can topple you over.
```
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFFlagDebugSimPrimalFeedback": "True",
    "DFIntDebugSimPrimalStiffnessMax": "0",
    "DFIntDebugSimPrimalStiffnessMin": "0",
    "DFIntMaximumFreefallMoveTimeInTenths": "1000"
}
```

### Clientsided Invisible
```
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1"
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

### Noclip (Probably Best One)
###### Adjust the value so you don't fall through the ground
```
{
        "DFFlagAssemblyExtentsExpansionStudHundredth": "-50"
}
```

### Noclip 2 
```
{
    "DFIntSimBroadPhasePairCountMax": "50"
}
```

### Noclip 3
```
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalStiffness": "0"
}
```

### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
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

<h1 align="center">Other FFlags</h2>

### Custom Disconnect Message
```
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```

### Voice Chat Distance
###### default: [Min 7 Max 80]
```
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```

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
###### Click the Beta badge or the 13+ badge to open the webview browser.
```
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```

### Sounds use physical velocity and become distorted
###### 2017
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

###### e.g
```
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```

### MTU
###### [Might Improve Ping]
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
###### You will still be kicked but the message wont show.
```
{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
```

### Quick Game Launch
###### BUGGY
```
{
    "FFlagEnableQuickGameLaunch": "True"
}
```

### Allows you to change voice chat distance
###### default: [Min 7 Max 80]
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
###### Clientsided
```
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```

### Verified Badge on everyone
###### Clientsided
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
###### https://roblox.fandom.com/wiki/Dynamic_Head
```
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
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
###### Removes the Experience Language option in settings
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
###### Only applies to games that has not changed the default zoom limit
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
###### default 1000
```
{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
```

### Removes the head roll limit for face tracking
###### Removes the head roll limit for face tracking
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

### Don't touch walls!!!
```
{
    "DFIntDebugSimPrimalNewtonIts": "-2147483647",
    "DFIntDebugSimPrimalToleranceInv": "-2147483647",
    "FFlagDebugSimDefaultPrimalSolver": "True"
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
###### Disable Drag Detectors
```
{
    "FFlagDragDetectors1": "False"
}
```

### Self Explanatory 5
###### Disabe CTM Climbin
```
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```

### Self Explanatory 6
###### Disabe Feedback Button in ESC
```
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```

<h1 align="center">Fast Flag Combinations</h2>

### Lower Ping
```
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
```
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
```
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
```
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

*Last Updated January 17th, 2023*

A list of all the deprecated API, organized by alphabet.

This topic is created simply for convenience. 

### Note: This list is entirely based on the API Reference Manual. If there's something I missed or outdated, let me know by replying to my topic on the DevForum and I'll update the topic.

DevForum Topic:
https://devforum.roblox.com/t/a-list-of-all-deprecated-classes-enums-events-functions-and-properties/1692454/

***

## Deprecated Classes

### A
- [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) (No replacement)


### B
- [BodyAngularVelocity](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity) 
  * Superseded by [AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity)
- [BodyForce](https://create.roblox.com/docs/reference/engine/classes/BodyForce) 
  * Superseded by [VectorForce](https://create.roblox.com/docs/reference/engine/classes/VectorForce)
- [BodyGyro](https://create.roblox.com/docs/reference/engine/classes/BodyGyro) 
  * Superseded by [AlignOrientation](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation)
- [BodyPosition](https://create.roblox.com/docs/reference/engine/classes/BodyPosition) 
  * Superseded by [AlignPosition](https://create.roblox.com/docs/reference/engine/classes/AlignPosition)
- [BodyThrust](https://create.roblox.com/docs/reference/engine/classes/BodyThrust) 
  * Superseded by [VectorForce](https://create.roblox.com/docs/reference/engine/classes/VectorForce)
- [BodyVelocity](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity) 
  * Superseded by [LinearVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocity)
### C
- [CustomEvent](https://create.roblox.com/docs/reference/engine/classes/CustomEvent) and [CustomEventReceiver](https://create.roblox.com/docs/reference/engine/classes/CustomEventReceiver) 
  * Use [BindableEvents](https://create.roblox.com/docs/reference/engine/classes/BindableEvent) instead
- [CylinderMesh](https://create.roblox.com/docs/reference/engine/classes/CylinderMesh)

***

### D
- [DoubleConstrainedValue](https://create.roblox.com/docs/reference/engine/classes/DoubleConstrainedValue) 
 * Use [math.clamp](https://create.roblox.com/docs/reference/engine/libraries/math#clamp) instead

***

### F
- [Flag](https://create.roblox.com/docs/reference/engine/classes/Flag) 
  * You need to create your own flag now
- [FlagStand](https://create.roblox.com/docs/reference/engine/classes/FlagStand) 
  * You need to Create your own flag stand now
- [FlagStandService](https://create.roblox.com/docs/reference/engine/classes/FlagStandService) (No replacement)
- [FloorWire](https://create.roblox.com/docs/reference/engine/classes/FloorWire) 
  * Use [Beams](https://create.roblox.com/docs/reference/engine/classes/Beam) instead
- All FormFactorProperties
- [FunctionalTest](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest) 
  * Use [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) instead

***

### G
- [GamePassService](https://create.roblox.com/docs/reference/engine/classes/GamePassService) 
  * Use [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) instead
- [Glue](https://create.roblox.com/docs/reference/engine/classes/Glue) 
  * Use [BallSocketConstraint](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint) as a partial replacement
- [GuiMain](https://create.roblox.com/docs/reference/engine/classes/GuiMain) 
  * Original Name For [ScreenGui](https://create.roblox.com/docs/reference/engine/classes/ScreenGui) which you should use instead.

***
### H
- [Hint](https://create.roblox.com/docs/reference/engine/classes/Hint) 
  * Use [TextLabels](https://create.roblox.com/docs/reference/engine/classes/TextLabel) instead
- [Hole](https://create.roblox.com/docs/reference/engine/classes/Hole) (No replacement)
- [Hopper](https://create.roblox.com/docs/reference/engine/classes/Hopper) 
  * Use [StarterPack](https://create.roblox.com/docs/reference/engine/classes/StarterPack) instead
- [HopperBin](https://create.roblox.com/docs/reference/engine/classes/HopperBin) 
  * Use [Tools](https://create.roblox.com/docs/reference/engine/classes/Tool) instead

***
### I
- [IntConstrainedValue](https://create.roblox.com/docs/reference/engine/classes/IntConstrainedValue) 

  * Use [math.clamp](https://create.roblox.com/docs/reference/engine/libraries/math#clamp) instead

***

### J
- [JointsService](https://create.roblox.com/docs/reference/engine/classes/JointsService) 

  * Use [Constraints and Attachments](https://create.roblox.com/docs/building-and-visuals/physics/mechanical-constraints)

 ***
### M
- [ManualGlue](https://create.roblox.com/docs/reference/engine/classes/ManualGlue)
 
  * Use [BallSocketConstraint](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint) as a partial replacement
- [ManualSurfaceJointInstance](https://create.roblox.com/docs/reference/engine/classes/ManualSurfaceJointInstance) 
  * The Base class for ManualGlue. Also has no replacement
- [ManualWeld](https://create.roblox.com/docs/reference/engine/classes/ManualWeld) 
  * Use [Weld](https://create.roblox.com/docs/reference/engine/classes/Weld) instead
- [Message](https://create.roblox.com/docs/reference/engine/classes/Message) 
  * Use [TextLabels](https://create.roblox.com/docs/reference/engine/classes/TextLabel) instead
- [MotorFeature](https://create.roblox.com/docs/reference/engine/classes/MotorFeature) (No Replacement)

***
### P
- [PointsService](https://create.roblox.com/docs/reference/engine/classes/PointsService) (Why :( ) (No replacement)
- [Plane](https://create.roblox.com/docs/reference/engine/classes/Plane)  (No replacement)
***
### R
- [RocketPropulsion](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion) 

  * Superseded by [LineForce](https://create.roblox.com/docs/reference/engine/classes/LineForce)
- [Rotate](https://create.roblox.com/docs/reference/engine/classes/Rotate)
- [RotateP](https://create.roblox.com/docs/reference/engine/classes/RotateP)
- [RotateV](https://create.roblox.com/docs/reference/engine/classes/RotateV)
***
### S
- [SelectionPartLasso](https://create.roblox.com/docs/reference/engine/classes/SelectionPartLasso) 

  * Use [Beams](https://create.roblox.com/docs/reference/engine/classes/Beam) instead
- [SelectionPointLasso](https://create.roblox.com/docs/reference/engine/classes/SelectionPointLasso)
- [SkateboardController](https://create.roblox.com/docs/reference/engine/classes/SkateboardController) 
  * It is advised to create your own Skateboard systems instead of this.
- [SkateboardPlatform](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform) (Used with SkateboardController)
  * It is advised to create your own Skateboard systems instead of this.
- [Skin](https://create.roblox.com/docs/reference/engine/classes/Skin)
  * (Superseded by [BodyColors](https://create.roblox.com/docs/reference/engine/classes/BodyColors))
- [Snap](https://create.roblox.com/docs/reference/engine/classes/Snap) 
  * Functionally identical to [welds](https://create.roblox.com/docs/reference/engine/classes/Weld), which you should use instead.
- [Speaker](https://create.roblox.com/docs/reference/engine/classes/Speaker)
- [Status](https://create.roblox.com/docs/reference/engine/classes/Status) 
  * Object made for Custom [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) Statuses, but was never finished. It as advised to use CollectionService instead for Custom [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) Statuses
***
### V
- [VoiceSource](https://create.roblox.com/docs/reference/engine/classes/VoiceSource)

***

## Deprecated Enums

### G
- [GearGenreSetting](https://create.roblox.com/docs/reference/engine/enums/GearGenreSetting) (No replacement)
- [GearType](https://create.roblox.com/docs/reference/engine/enums/GearType) (No replacement)
- [Genre](https://create.roblox.com/docs/reference/engine/enums/Genre) (No replacement)
***
### P
- [PriviledgeType](https://create.roblox.com/docs/reference/engine/enums/PrivilegeType) (No replacement)
***
### S
- [SaveFilter](https://create.roblox.com/docs/reference/engine/enums/SaveFilter) (Has no known usage and its purpose is unknown)
- [Status](https://create.roblox.com/docs/reference/engine/enums/Status)

    * Status is an unfinished object designed to store custom Humanoid statuses. It has been depreciated and should not be used by developers in new work.  Developers looking to implement custom Humanoid statuses should use [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) which provides a more flexible and robust system for tagging objects.

- [SoundType](https://github.com/MaximumADHD/Roblox-Client-Tracker/commit/d20ed8dec60f10822d140438b936852480166d0a)
***

## Deprecated EnumItems

### G
- [GearGenreSetting.AllGenres](https://robloxapi.github.io/ref/enum/GearGenreSetting.html#member-AllGenres)
- [GearType.BuildingTools](https://robloxapi.github.io/ref/enum/GearType.html#member-BuildingTools)
- [GearType.Explosives](https://robloxapi.github.io/ref/enum/GearType.html#member-Explosives)
- [GearType.MeleeWeapons](https://robloxapi.github.io/ref/enum/GearType.html#member-MeleeWeapons)
- [GearType.MusicalInstruments](https://robloxapi.github.io/ref/enum/GearType.html#member-MusicalInstruments)
- [GearType.NavigationEnhancers](https://robloxapi.github.io/ref/enum/GearType.html#member-NavigationEnhancers)
- [GearType.PowerUps](https://robloxapi.github.io/ref/enum/GearType.html#member-PowerUps)
- [GearType.RangedWeapons](https://robloxapi.github.io/ref/enum/GearType.html#member-RangedWeapons)
- [GearType.SocialItems](https://robloxapi.github.io/ref/enum/GearType.html#member-SocialItems)
- [GearType.Transport](https://robloxapi.github.io/ref/enum/GearType.html#member-Transport)

### L
- [LevelOfDetailSetting.High](https://robloxapi.github.io/ref/enum/LevelOfDetailSetting.html#member-High)
- [LevelOfDetailSetting.Low](https://robloxapi.github.io/ref/enum/LevelOfDetailSetting.html#member-Low)
- [LevelOfDetailSetting.Medium](https://robloxapi.github.io/ref/enum/LevelOfDetailSetting.html#member-Medium)

### M
- [MeshType.CornerWedge](https://robloxapi.github.io/ref/enum/MeshType.html#member-CornerWedge)
- [MeshType.ParallelRamp](https://robloxapi.github.io/ref/enum/MeshType.html#member-ParallelRamp)
- [MeshType.Prism](https://robloxapi.github.io/ref/enum/MeshType.html#member-Prism)
- [MeshType.Pyramid](https://robloxapi.github.io/ref/enum/MeshType.html#member-Pyramid)
- [MeshType.RightAngleRamp](https://robloxapi.github.io/ref/enum/MeshType.html#member-RightAngleRamp)

### P
- [PathStatus.ClosestNoPath](https://robloxapi.github.io/ref/enum/PathStatus.html#member-ClosestNoPath)
- [PathStatus.ClosestOutOfRange](https://robloxapi.github.io/ref/enum/PathStatus.html#member-ClosestOutOfRange)
- [PathStatus.FailFinishNotEmpty](https://robloxapi.github.io/ref/enum/PathStatus.html#member-FailFinishNotEmpty)
- [PathStatus.FailStartNotEmpty](https://robloxapi.github.io/ref/enum/PathStatus.html#member-FailStartNotEmpty)

### S
- [SortOrder.Custom](https://robloxapi.github.io/ref/enum/SortOrder.html#member-Custom)
- [Status.Confusion](https://create.roblox.com/docs/reference/engine/enums/Status)
- [Status.Poison](https://create.roblox.com/docs/reference/engine/enums/Status)

### T
- [Technology.Legacy](https://robloxapi.github.io/ref/enum/Technology.html#member-Legacy)

### U
- [UITheme.Dark](https://robloxapi.github.io/ref/enum/UITheme.html#member-Dark)
- [UITheme.Light](https://robloxapi.github.io/ref/enum/UITheme.html#member-Light)

***

## Deprecated Callbacks

- [DataModel.OnClose](https://create.roblox.com/docs/reference/engine/classes/DataModel#OnClose) 

  * Use [DataModel:BindToClose](https://create.roblox.com/docs/reference/engine/classes/DataModel#BindToClose) instead
***

## Deprecated Events

### A
- [AdService.VideoAdClosed](https://create.roblox.com/docs/reference/engine/classes/AdService#VideoAdClosed)

  * AdService is entirely deprecated 
- [AnimationController.AnimationPlayed](https://create.roblox.com/docs/reference/engine/classes/AnimationController#AnimationPlayed)
***
### B
- [BasePart.LocalSimulationTouched](https://create.roblox.com/docs/reference/engine/classes/BasePart#LocalSimulationTouched)

  * Use [BasePart.Touched](https://create.roblox.com/docs/reference/engine/classes/BasePart#Touched) instead
- [BasePart.OutfitChanged](https://create.roblox.com/docs/reference/engine/classes/BasePart#OutfitChanged)
- [BasePart.StoppedTouching](https://create.roblox.com/docs/reference/engine/classes/BasePart#StoppedTouching)
  * Use [BasePart.TouchEnded](https://create.roblox.com/docs/reference/engine/classes/BasePart#TouchEnded) instead
***
### C
- [CollectionService.ItemAdded](https://create.roblox.com/docs/reference/engine/classes/CollectionService#ItemAdded)
- [CollectionService.ItemRemoved](https://create.roblox.com/docs/reference/engine/classes/CollectionService#ItemRemoved)
***
### D
- [DataModel.AllowGearTypeChanged](https://create.roblox.com/docs/reference/engine/classes/DataModel#AllowedGearTypeChanged)
- [DataModel.ItemChanged](https://create.roblox.com/docs/reference/engine/classes/DataModel#ItemChanged)

  * Use [Instance.Changed](https://create.roblox.com/docs/reference/engine/classes/Instance#Changed) instead
***
### G
- [GuiObject.DragBegin](https://create.roblox.com/docs/reference/engine/classes/GuiObject#DragBegin)
- [GuiObject.DragStopped](https://create.roblox.com/docs/reference/engine/classes/GuiObject#DragStopped)
- [GuiService.BrowserWindowClosed](https://create.roblox.com/docs/reference/engine/classes/GuiService#BrowserWindowClosed)
- [GuiService.ErrorMessageChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#ErrorMessageChanged)
***
### H
- [Humanoid.AnimationPlayed](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AnimationPlayed)
- [Humanoid.CustomStatusAdded](https://create.roblox.com/docs/reference/engine/classes/Humanoid#CustomStatusAdded)
- [Humanoid.CustomStatusRemoved](https://create.roblox.com/docs/reference/engine/classes/Humanoid#CustomStatusRemoved)
- [Humanoid.StatusAdded](https://create.roblox.com/docs/reference/engine/classes/Humanoid#StatusAdded)
- [Humanoid.StatusRemoved](https://create.roblox.com/docs/reference/engine/classes/Humanoid#StatusRemoved)
***
### M
- [MarketplaceService.PromptProductPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptProductPurchaseFinished)

   * Use the [MarketplaceService.ProcessReceipt](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ProcessReceipt) Callback to process purchases instead
- [Mouse.KeyDown](https://create.roblox.com/docs/reference/engine/classes/Mouse#KeyDown)
   * Use [UserInputService](https://create.roblox.com/docs/reference/engine/classes/UserInputService) instead
- [Mouse.KeyUp](https://create.roblox.com/docs/reference/engine/classes/Mouse#KeyUp)
   * Use [UserInputService](https://create.roblox.com/docs/reference/engine/classes/UserInputService) instead
***
### P
- [PlayerGui.TopbarTransparencyChangedSignal](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#TopbarTransparencyChangedSignall)
***
### S
- [SkateboardPlatform.equipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#equipped)

  * SkateboardPlatform is entirely deprecated
- [SkateboardPlatform.unequipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#unequipped)
  * SkateboardPlatform is entirely deprecated 
***
### V
- [VoiceChatInternal.ParticipantsStateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#ParticipantsStateChanged)
- [VoiceChatInternal.PlayerMicActivitySignalChange](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#PlayerMicActivitySignalChange)
- [VoiceChatInternal.StateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#StateChanged)
***

## Deprecated Functions

### A
- [AdService.ShowVideoAd](https://robloxapi.github.io/ref/class/AdService.html#member-ShowVideoAd) 

  * (AdService is entirely deprecated)
- [AnalyticsService.FireEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireEvent) 
  * Use the [other methods](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#functions) in AnalyticsService instead
- [AnimationClipProvider.GetAnimationClip](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationClip) 
   * Use [GetAnimationClipAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationClipAsync) instead
- [AnimationClipProvider.GetAnimationClipById](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationClipById)  
  * Use [GetAnimationClipAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationClipAsync) instead
- [AnimationController.GetPlayingAnimationTracks](https://create.roblox.com/docs/reference/engine/classes/AnimationController#GetPlayingAnimationTracks)
- [AnimationController.LoadAnimation](https://create.roblox.com/docs/reference/engine/classes/AnimationController#LoadAnimation) 
  * Use [Animator:LoadAnimation()](https://create.roblox.com/docs/reference/engine/classes/Animator#LoadAnimation) instead
- [AssetService.GetCreatorAssetID](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetCreatorAssetID)
- [Attachment.GetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#GetAxis)
- [Attachment.GetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#GetSecondaryAxis)
- [AvatarEditorService.GetRecommendedAssets](https://robloxapi.github.io/ref/class/AvatarEditorService.html#member-GetRecommendedAssets)
- [AvatarEditorService.GetRecommendedBundles](https://robloxapi.github.io/ref/class/AvatarEditorService.html#member-GetRecommendedBundles)
- [Attachment.SetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetAxis)
- [Attachment.SetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetSecondaryAxis)

### B
- [BadgeService.IsDisabled](https://create.roblox.com/docs/reference/engine/classes/BadgeService#IsDisabled)

  * To check is a Badge is disabled, call [BadgeService:GetBadgeInfoAsync()](https://create.roblox.com/docs/reference/engine/classes/BadgeService#GetBadgeInfoAsync) and check the IsEnabled field
- [BadgeService.IsLegal](https://create.roblox.com/docs/reference/engine/classes/BadgeService#IsLegal)
- [BadgeService.UserHasBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadge) 
  * Use [BadgeService:UserHasBadgeAsync()](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadgeAsync) instead
- [BasePart.GetRenderCFrame](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetRenderCFrame)
- [BasePart.breakJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#breakJoints) 
  * Use [BasePart:BreakJoints()](https://create.roblox.com/docs/reference/engine/classes/BasePart#BreakJoints) instead
- [BasePart.getMass](https://create.roblox.com/docs/reference/engine/classes/BasePart#getMass) 
  * Use [BasePart:GetMass()](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetMass) instead
- [BasePart.makeJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#makeJoints) 
  * Use [BasePart:MakeJoints()](https://create.roblox.com/docs/reference/engine/classes/BasePart#MakeJoints) instead
- [BasePart.resize](https://create.roblox.com/docs/reference/engine/classes/BasePart#resize) 
   * Use [BasePart:Resize()](https://create.roblox.com/docs/reference/engine/classes/BasePart#Resize) instead
- [BodyPosition:lastForce](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#lastForce)
  * BodyPosition is entirely deprecated

### C
- [Camera.GetLargestCutoffDistance](https://create.roblox.com/docs/reference/engine/classes/Camera#GetLargestCutoffDistance)
- [Camera.Interpolate](https://create.roblox.com/docs/reference/engine/classes/Camera#Interpolate) 

   * Use [TweenService](https://create.roblox.com/docs/reference/engine/classes/TweenService) to smoothly animate the Camera instead
- [Camera.PanUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#PanUnits)
- [Camera.TiltUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#TiltUnits)
- [Chat.FilterStringForPlayerAsync](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringForPlayerAsync) 
  * Use [Chat:FilterStringAsync()](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringAsync) and [Chat:FilterStringForBroadcast()](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringForBroadcast) instead
- [CollectionService.GetCollection](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetCollection) 
   * Use [CollectionService:GetTagged()](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagged) instead
- [ContentProvider.Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload) 
   * Use [ContentProvider:PreloadAsync()](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#PreloadAsync) instead
- [ContextActionService.BindActionToInputTypes](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionToInputTypes) 
    * Use [ContextActionService:BindAction()](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindAction) instead
- [Controller.bindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#bindButton) 
     * Use [Controller:BindButton()](https://create.roblox.com/docs/reference/engine/classes/Controller#BindButton) instead
- [Controller.getButton](https://create.roblox.com/docs/reference/engine/classes/Controller#getButton) 
     * Use [Controller:GetButton()](https://create.roblox.com/docs/reference/engine/classes/Controller#GetButton) instead

### D
- [DataModel.GetMessage](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetMessage)
- [DataModel.GetRemoteBuildMode](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetRemoteBuildMode)

  * Use [RunService:IsServer()](https://create.roblox.com/docs/reference/engine/classes/RunService#IsServer) to see if your code is running on the server instead
- [DataModel.IsGearTypeAllowed](https://create.roblox.com/docs/reference/engine/classes/DataModel#IsGearTypeAllowed)
- [DataModel.SavePlace](https://create.roblox.com/docs/reference/engine/classes/DataModel#SavePlace)
- [Debris.addItem](https://create.roblox.com/docs/reference/engine/classes/Debris#addItem)
  * Use [Debris:AddItem()](https://create.roblox.com/docs/reference/engine/classes/Debris#AddItem) instead
- [DebuggerManager.StepOut](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOut)
- [DebuggerManager.StepOver]()
https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOver
### G
- [GamePassService.PlayerHasPass](https://create.roblox.com/docs/reference/engine/classes/GamePassService#PlayerHasPass)

  * Use [MarketplaceService:UserOwnsGamepassAsync()](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#UserOwnsGamePassAsync) instead
- [GlobalDataStore.OnUpdate](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#OnUpdate)

  * Use [MessagingService](https://create.roblox.com/docs/reference/engine/classes/MessagingService) to publish and subscribe to topics to receive near real-time updates.
- [GuiService.GetErrorMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetErrorMessage)
- [GuiService.OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenBrowserWindow)
- [GuiService.OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenNativeOverlay)

### H
- [Humanoid.AddCustomStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AddCustomStatus)
- [Humanoid.AddStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AddStatus)
- [Humanoid.GetPlayingAnimationTracks](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetPlayingAnimationTracks)
- [Humanoid.GetStatuses](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetStatuses)
- [Humanoid.HasCustomStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HasCustomStatus)
- [Humanoid.HasStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HasStatus)
- [Humanoid.LoadAnimation](https://create.roblox.com/docs/reference/engine/classes/Humanoid#LoadAnimation)

  *  Use [Animator:LoadAnimation()](https://create.roblox.com/docs/reference/engine/classes/Animator#LoadAnimation) instead
- [Humanoid.RemoveCustomStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RemoveCustomStatus)
- [Humanoid.RemoveStatus](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RemoveStatus)
- [Humanoid.loadAnimation](https://create.roblox.com/docs/reference/engine/classes/Humanoid#loadAnimation)
  *  Use [Animator:LoadAnimation()](https://create.roblox.com/docs/reference/engine/classes/Animator#LoadAnimation) instead
- [Humanoid.takeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#takeDamage)
  * Use [Humanoid:TakeDamage()](https://create.roblox.com/docs/reference/engine/classes/Humanoid#TakeDamage) instead

### I
- [InsertService.ApproveAssetId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetId)
- [InsertService.ApproveAssetVersionId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetVersionId)
- [InsertService.GetBaseCategories](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetBaseCategories)
- [InsertService.GetUserCategories](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetUserCategories)
- [InsertService.Insert](https://create.roblox.com/docs/reference/engine/classes/InsertService#Insert)

  * Use [InsertService:LoadAsset()](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadAsset) instead
- [InsertService.loadAsset](https://robloxapi.github.io/ref/class/InsertService.html#member-loadAsset)
  * Use [InsertService:LoadAsset()](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadAsset) instead
- [Instance.Remove](https://create.roblox.com/docs/reference/engine/classes/Instance#Remove)
  * Use [Instance:Destroy()](https://create.roblox.com/docs/reference/engine/classes/Instance#Destroy) and [Instance:ClearAllChildren()](https://create.roblox.com/docs/reference/engine/classes/Instance#ClearAllChildren) instead
- [Instance.children](https://create.roblox.com/docs/reference/engine/classes/Instance#children) (Use [Instance:GetChildren()](https://create.roblox.com/docs/reference/engine/classes/Instance#GetChildren) instead)

### K
- [KeyframeSequenceProvider.GetKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequence)

  * Use [KeyFrameSequenceProvider:GetKeyframeSequenceAsync()](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceAsync) instead
- [KeyframeSequenceProvider.GetKeyframeSequenceById](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceById)
  * Use [KeyFrameSequenceProvider:GetKeyframeSequenceAsync()](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceAsync) instead

### L
- [LayerCollector.GetLayoutNodeTree](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#GetLayoutNodeTree)
- [Lighting.getMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#getMinutesAfterMidnight)

  * Use [Lighting:GetMinutesAfterMidnight()](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMinutesAfterMidnight) instead
- [Lighting.setMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#setMinutesAfterMidnight)
  * Use [Lighting:SetMinutesAfterMidnight()](https://create.roblox.com/docs/reference/engine/classes/Lighting#SetMinutesAfterMidnight) instead
- [LocalizationTable.GetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetContents)
  * Use [LocalizationTable:GetEntries()](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetEntries) instead
- [LocalizationTable.GetString](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetString)
  * Use [LocalizationTable:GetTranslator()](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetTranslator) instead
- [LocalizationTable.RemoveKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveKey)
  * Use [LocalizationTable:RemoveEntry()](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntry) instead
- [LocalizationTable.SetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetContents)
  * Use [LocalizationTable:SetEntries()](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntries) instead
- [LocalizationTable.SetEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntry)
  * Use [LocalizationTable:SetEntries()](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntries) instead

### M
- [Model.GetModelCFrame](https://create.roblox.com/docs/reference/engine/classes/Model#GetModelCFrame)

  * Use [PVInstance:GetPivot()](https://create.roblox.com/docs/reference/engine/classes/PVInstance#GetPivot) instead
- [Model.GetModelSize](https://create.roblox.com/docs/reference/engine/classes/Model#GetModelSize)
- [Model.GetPrimaryPartCFrame](https://create.roblox.com/docs/reference/engine/classes/Model#GetPrimaryPartCFrame)
  * Use [PVInstance:GetPivot()](https://create.roblox.com/docs/reference/engine/classes/PVInstance#GetPivot) instead
- [Model.SetPrimaryPartCFrame](https://create.roblox.com/docs/reference/engine/classes/Model#SetPrimaryPartCFrame)
  * Use [PVInstance:PivotTo()](https://create.roblox.com/docs/reference/engine/classes/PVInstance#PivotTo) instead
- [Model.ResetOrientationToIdentity](https://create.roblox.com/docs/reference/engine/classes/Model#ResetOrientationToIdentity)
- [Model.SetIdentityOrientation](hhttps://create.roblox.com/docs/reference/engine/classes/Model#SetIdentityOrientation)
- [Model.breakJoints](https://create.roblox.com/docs/reference/engine/classes/Model#breakJoints)
  * Use [Model:BreakJoints()](https://create.roblox.com/docs/reference/engine/classes/Model#BreakJoints) instead
- [Model.makeJoints](https://create.roblox.com/docs/reference/engine/classes/Model#makeJoints)
  * Use [Model:MakeJoints()](https://create.roblox.com/docs/reference/engine/classes/Model#MakeJoints) instead
- [Model.move](https://create.roblox.com/docs/reference/engine/classes/Model#move)
  * Use [Model:MoveTo()](https://create.roblox.com/docs/reference/engine/classes/Model#MoveTo) instead
- [Model.moveTo](https://create.roblox.com/docs/reference/engine/classes/Model#moveTo)
  * Use [Model:MoveTo()](https://create.roblox.com/docs/reference/engine/classes/Model#MoveTo) instead

### P
- [Path.GetPointCoordinates](https://create.roblox.com/docs/reference/engine/classes/Path#GetPointCoordinates)

  * Use [Path:GetWaypoints()](https://create.roblox.com/docs/reference/engine/classes/Path#GetWaypoints) instead
- [PathfindingService.ComputeRawPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeRawPathAsync)
  * Use [PathfindingService:FindPathAsync()](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#FindPathAsync) instead
- [PathfindingService.ComputerSmoothPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeSmoothPathAsync)
  * Use [PathfindingService:FindPathAsync()](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#FindPathAsync) instead
- [Player.IsBestFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsBestFriendsWith)
- [Player.IsUserAvailableForExperiment](https://robloxapi.github.io/ref/class/Player.html#member-IsUserAvailableForExperiment)
- [Player.LoadBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#LoadBoolean)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.LocalCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterAppearance)
- [Player.LoadData](https://create.roblox.com/docs/reference/engine/classes/Player#LoadData)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.LoadInstance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadInstance)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.LoadNumber](https://create.roblox.com/docs/reference/engine/classes/Player#LoadNumber)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.LoadString](https://create.roblox.com/docs/reference/engine/classes/Player#LoadString)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.SaveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#SaveBoolean)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.SaveData](https://create.roblox.com/docs/reference/engine/classes/Player#SaveData)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.SaveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#SaveInstance)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.SaveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#SaveNumber)
- [Player.SaveString](https://create.roblox.com/docs/reference/engine/classes/Player#SaveString)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.SetUnder13](https://create.roblox.com/docs/reference/engine/classes/Player#SetUnder13)
- [Player.WaitForDataReady](https://create.roblox.com/docs/reference/engine/classes/Player#WaitForDataReady)
  * Use [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) to load and save Player Data instead
- [Player.isFriendsWith](https://robloxapi.github.io/ref/class/Player.html#member-isFriendsWith)
- [PlayerGui.GetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#GetTopbarTransparency)
- [PlayerGui.SetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SetTopbarTransparency)
- [Players.GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync)
- [Players.getPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#getPlayers)
  * Use [Players:GetPlayers()](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers) instead
- [Players.playerfromCharacter](https://create.roblox.com/docs/reference/engine/classes/Players#playerFromCharacter)
  * Use [Players:GetPlayerFromCharacter()](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerFromCharacter) instead
- [Players.players](https://create.roblox.com/docs/reference/engine/classes/Players#players)
  * Use [Players:GetPlayers()](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers) instead
- [Plugin.GetStudioUserId](https://create.roblox.com/docs/reference/engine/classes/Plugin#GetStudioUserId)
- [PluginManager.CreatePlugin](https://create.roblox.com/docs/reference/engine/classes/PluginManager#CreatePlugin)
- [PluginManagerInterface.CreatePlugin](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface#CreatePlugin)
- [PointsService.AwardPoints](https://create.roblox.com/docs/reference/engine/classes/PointsService#AwardPoints)
- [PointsService.GetAwardablePoints](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetAwardablePoints)
- [PointsService.GetGamePointBalance](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetGamePointBalance)
- [PointsService.GetPointBalance](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetPointBalance)

### R
- [RocketPropulsion.fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#fire)

  * Use [RocketPropulsion:Fire()](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Fire) instead

### S
- [ServiceProvider.getService](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider#getService)

  *  Use [ServiceProvider:GetService()](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider#GetService) instead
- [ServiceProvider.service](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider#service)
  * Use [ServiceProvider:GetService()](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider#GetService) instead
- [Sound.pause](https://create.roblox.com/docs/reference/engine/classes/Sound#pause)
  * Use [Sound:Pause()](https://create.roblox.com/docs/reference/engine/classes/Sound#Pause) instead
- [Sound.play](https://create.roblox.com/docs/reference/engine/classes/Sound#play)
  * Use [Sound:Play()](https://create.roblox.com/docs/reference/engine/classes/Sound#Play) instead
- [Sound.stop](https://create.roblox.com/docs/reference/engine/classes/Sound#stop)
  * Use [Sound:Stop()](https://create.roblox.com/docs/reference/engine/classes/Sound#Stop) instead instead

### T
- [Teams.RebalanceTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#RebalanceTeams)
- [Terrain.AutowedgeCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCell)
- [Terrain.AutowedgeCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCells)
- [Terrain.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/Terrain#ConvertToSmooth)
- [Terrain.GetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetCell)
- [Terrain.GetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetWaterCell)
- [Terrain.SetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCell)
- [Terrain.SetCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCells)
- [Terrain.SetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetWaterCell)
- [TerrainRegion.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#ConvertToSmooth)

### U
- [UIGridStyleLayout.ApplyLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#ApplyLayout)
- [UIGridStyleLayout.SetCustomSortFunction](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#SetCustomSortFunction)

### V
- [VoiceChatInternal.GetAndClearCallFailureMessage](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetAndClearCallFailureMessage)
- [VoiceChatInternal.GetAudioProcessingSettings](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetAudioProcessingSettings)
- [VoiceChatInternal.GetMicDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetMicDevices)
- [VoiceChatInternal.GetParticipants](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetParticipants)
- [VoiceChatInternal.GetSpeakerDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetSpeakerDevices)
- [VoiceChatInternal.GetVoiceChatApiVersion](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetVoiceChatApiVersion)
- [VoiceChatInternal.GetVoiceChatAvailable](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#GetVoiceChatAvailable)
- [VoiceChatInternal.IsPublishPaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#IsPublishPaused)
- [VoiceChatInternal.IsSubscribePaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#IsSubscribePaused)
- [VoiceChatInternal.JoinByGroupId](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#JoinByGroupId)
- [VoiceChatInternal.JoinByGroupIdToken](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#JoinByGroupIdToken)
- [VoiceChatInternal.Leave](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#Leave)
- [VoiceChatInternal.PublishPause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#PublishPause)
- [VoiceChatInternal.SetMicDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#SetMicDevice)
- [VoiceChatInternal.SetSpeakerDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#SetSpeakerDevice)
- [VoiceChatInternal.SubscribePause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#SubscribePause)
- [VoiceChatInternal.SubscribePauseAll](https://create.roblox.com/docs/reference/engine/classes/VoiceChatInternal#SubscribePauseAll)

### W
- [WorldRoot.FindPartOnRay](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRay)

  * Use [WorldRoot:Raycast()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast) along with [RaycastParams](https://create.roblox.com/docs/reference/engine/datatypes/RaycastParams) instead
- [WorldRoot.FindPartOnRayWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithIgnoreList)
- [WorldRoot.FindPartOnRayWithWhitelist](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithWhitelist)
  * Use [WorldRoot:Raycast()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast) along with [RaycastParams](https://create.roblox.com/docs/reference/engine/datatypes/RaycastParams) instead
- [WorldRoot.FindPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3)
  * Use [WorldRoot:GetPartBoundsInBox()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) along with [OverlapParams](https://create.roblox.com/docs/reference/engine/datatypes/OverlapParams) instead
- [WorldRoot.FindPartsInRegion3WithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithIgnoreList)
  * Use [WorldRoot:GetPartBoundsInBox()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) along with [OverlapParams](https://create.roblox.com/docs/reference/engine/datatypes/OverlapParams) instead
- [WorldRoot.FindPartsInRegion3WithWhiteList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithWhiteList)
  * Use [WorldRoot:GetPartBoundsInBox()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) along with [OverlapParams](https://create.roblox.com/docs/reference/engine/datatypes/OverlapParams) instead
- [WorldRoot.IsRegion3Empty](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IsRegion3Empty)
  * Use [WorldRoot:GetPartBoundsInBox()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) along with [OverlapParams](https://create.roblox.com/docs/reference/engine/datatypes/OverlapParams) instead
- [WorldRoot.IsRegion3EmptyWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IsRegion3EmptyWithIgnoreList)
  * Use [WorldRoot:GetPartBoundsInBox()](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) along with [OverlapParams](https://create.roblox.com/docs/reference/engine/datatypes/OverlapParams) instead
***

## Deprecated Properties

### A
- [AnalyticsService.ApiKey](https://robloxapi.github.io/ref/class/AnalyticsService.html#member-ApiKey)

- Attachment
     - [Rotation](https://robloxapi.github.io/ref/class/Attachment.html#member-Rotation)
     - [WorldRotation](https://robloxapi.github.io/ref/class/Attachment.html#member-WorldRotation)

### B
- BasePart
     - [BackParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-BackParamA)
     - [BackParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-BackParamB)
     - [BackSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-BackSurfaceInput)
     - [BottomParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-BottomParamA)
     - [BottomParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-BottomParamB) 
     - [BottomSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-BottomSurfaceInput)
     - [Elasticity](https://robloxapi.github.io/ref/class/BasePart.html#member-Elasticity)
     - [Friction](https://robloxapi.github.io/ref/class/BasePart.html#member-Friction)
     - [FrontParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-FrontParamA)
     - [FrontParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-FrontParamB)
     - [FrontSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-FrontSurfaceInput)
     - [LeftParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-LeftParamA)
     - [LeftParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-LeftParamB)
     - [LeftSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-LeftSurfaceInput)
     - [RightParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-RightParamA)
     - [RightParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-RightParamB)
     - [RightSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-RightSurfaceInput)
     - [RotVelocity](https://robloxapi.github.io/ref/class/BasePart.html#member-RotVelocity)
     - [SpecificGravity](https://robloxapi.github.io/ref/class/BasePart.html#member-SpecificGravity)
     - [TopParamA](https://robloxapi.github.io/ref/class/BasePart.html#member-TopParamA)
     - [TopParamB](https://robloxapi.github.io/ref/class/BasePart.html#member-TopParamB)
     - [TopSurfaceInput](https://robloxapi.github.io/ref/class/BasePart.html#member-TopSurfaceInput)
     - [Velocity](https://robloxapi.github.io/ref/class/BasePart.html#member-Velocity)
     - [brickColor](https://robloxapi.github.io/ref/class/BasePart.html#member-brickColor)

- BodyAngularVelocity
     - [angularvelocity](https://robloxapi.github.io/ref/class/BodyAngularVelocity.html#member-angularvelocity)
     - [maxTorque](https://robloxapi.github.io/ref/class/BodyAngularVelocity.html#member-maxTorque)

- [BodyForce.force](https://robloxapi.github.io/ref/class/BodyForce.html#member-force)

- BodyGyro
     - [cframe](https://robloxapi.github.io/ref/class/BodyGyro.html#member-cframe)
     - [maxTorque](https://robloxapi.github.io/ref/class/BodyGyro.html#member-maxTorque)

- BodyPosition
     - [maxForce](https://robloxapi.github.io/ref/class/BodyPosition.html#member-maxForce)
     - [position](https://robloxapi.github.io/ref/class/BodyPosition.html#member-position)

- BodyThrust
     - [force](https://robloxapi.github.io/ref/class/BodyThrust.html#member-force)
     - [location](https://robloxapi.github.io/ref/class/BodyThrust.html#member-location)

- BodyVelocity
     - [maxForce](https://robloxapi.github.io/ref/class/BodyVelocity.html#member-maxForce)
     - [velocity](https://robloxapi.github.io/ref/class/BodyVelocity.html#member-velocity)

### C
- Camera
     - [CoordinateFrame](https://robloxapi.github.io/ref/class/Camera.html#member-CoordinateFrame)
     - [focus](https://robloxapi.github.io/ref/class/Camera.html#member-focus)

### D
- DataModel
     - [GearGenreSetting](https://robloxapi.github.io/ref/class/DataModel.html#member-GearGenreSetting)
     - [VIPServerId](https://robloxapi.github.io/ref/class/DataModel.html#member-VIPServerId)
     - [VIPServerOwnerId](https://robloxapi.github.io/ref/class/DataModel.html#member-VIPServerOwnerId)
     - [lighting](https://robloxapi.github.io/ref/class/DataModel.html#member-lighting)
     - [workspace](https://robloxapi.github.io/ref/class/DataModel.html#member-workspace)  

- [DataStoreService.LegacyNamingScheme](https://robloxapi.github.io/ref/class/DataStoreService.html#member-LegacyNamingScheme)

- [Debris.MaxItems](https://robloxapi.github.io/ref/class/Debris.html#member-MaxItems)

- Decal
     - [Shiny](https://robloxapi.github.io/ref/class/Decal.html#member-Shiny)
     - [Specular](https://robloxapi.github.io/ref/class/Decal.html#member-Specular)

### F
- [Fire.size](https://robloxapi.github.io/ref/class/Fire.html#member-size)

- FormFactorPart
     - [FormFactor](https://robloxapi.github.io/ref/class/FormFactorPart.html#member-FormFactor)
     - [formFactor](https://robloxapi.github.io/ref/class/FormFactorPart.html#member-formFactor)

### G
- [GuiBase2d.Localize](https://robloxapi.github.io/ref/class/GuiBase2d.html#member-Localize)

- [GuiBase3d.Color](https://robloxapi.github.io/ref/class/GuiBase3d.html#member-Color)

- GuiObject
     - [BackgroundColor](https://robloxapi.github.io/ref/class/GuiObject.html#member-BackgroundColor)
     - [BorderColor](https://robloxapi.github.io/ref/class/GuiObject.html#member-BorderColor)
     - [Draggable](https://robloxapi.github.io/ref/class/GuiObject.html#member-Draggable)

- GuiService
     - [IsModalDialog](https://robloxapi.github.io/ref/class/GuiService.html#member-IsModalDialog)
     - [IsWindows](https://robloxapi.github.io/ref/class/GuiService.html#member-IsWindows)

### H
- Humanoid
     - [CollisionType](https://robloxapi.github.io/ref/class/Humanoid.html#member-CollisionType)
     - [LeftLeg](https://robloxapi.github.io/ref/class/Humanoid.html#member-LeftLeg)
     - [RightLeg](https://robloxapi.github.io/ref/class/Humanoid.html#member-RightLeg)
     - [Torso](https://robloxapi.github.io/ref/class/Humanoid.html#member-Torso)
     - [maxHealth](https://robloxapi.github.io/ref/class/Humanoid.html#member-maxHealth)

### I
- [InsertService.AllowInsertFreeModels](https://robloxapi.github.io/ref/class/InsertService.html#member-AllowInsertFreeModels)

- Instance
     - [DataCost](https://robloxapi.github.io/ref/class/Instance.html#member-DataCost)
     - [archivable](https://robloxapi.github.io/ref/class/Instance.html#member-archivable)
     - [className](https://robloxapi.github.io/ref/class/Instance.html#member-className)

### J
- [JointInstance.part1](https://robloxapi.github.io/ref/class/JointInstance.html#member-part1)

### L
- Lighting
     - [Outlines](https://robloxapi.github.io/ref/class/Lighting.html#member-Outlines)
     - [ShadowColor](https://robloxapi.github.io/ref/class/Lighting.html#member-ShadowColor)

- LocalizationTable
     - [DevelopmentLanguage](https://robloxapi.github.io/ref/class/LocalizationTable.html#member-DevelopmentLanguage)
     - [Root](https://robloxapi.github.io/ref/class/LocalizationTable.html#member-Root)

### M
- [MeshPart.MeshID](https://robloxapi.github.io/ref/class/MeshPart.html#member-MeshID)

- Mouse
     - [hit](https://robloxapi.github.io/ref/class/Mouse.html#member-hit)
     - [target](https://robloxapi.github.io/ref/class/Mouse.html#member-target)|

### P
- [ParticleEmitter.VelocitySpread](https://robloxapi.github.io/ref/class/ParticleEmitter.html#member-VelocitySpread)

- [PathfindingService.EmptyCutoff](https://robloxapi.github.io/ref/class/PathfindingService.html#member-EmptyCutoff)

- Player
     - [AppearanceDidLoad](https://robloxapi.github.io/ref/class/Player.html#member-AppearanceDidLoad)
     - [CharacterAppearance](https://robloxapi.github.io/ref/class/Player.html#member-CharacterAppearance)
     - [DataComplexity](https://robloxapi.github.io/ref/class/Player.html#member-DataComplexity)
     - [DataComplexityLimit](https://robloxapi.github.io/ref/class/Player.html#member-DataComplexityLimit)
     - [DataReady](https://robloxapi.github.io/ref/class/Player.html#member-DataReady)
     - [userId](https://robloxapi.github.io/ref/class/Player.html#member-userId)

- Players
     - [NumPlayers](https://robloxapi.github.io/ref/class/Players.html#member-NumPlayers)
     - [localPlayer](https://robloxapi.github.io/ref/class/Players.html#member-localPlayer)
     - [numPlayers](https://robloxapi.github.io/ref/class/Players.html#member-numPlayers)

- [Pose.MaskWeight](https://robloxapi.github.io/ref/class/Pose.html#member-MaskWeight)

### S
- [SelectionBox.SurfaceColor](https://robloxapi.github.io/ref/class/SelectionBox.html#member-SurfaceColor)

- [SelectionSphere.SurfaceColor](https://robloxapi.github.io/ref/class/SelectionSphere.html#member-SurfaceColor)

- Sound
     - [EmitterSize](https://robloxapi.github.io/ref/class/Sound.html#member-EmitterSize)
     - [MaxDistance](https://robloxapi.github.io/ref/class/Sound.html#member-MaxDistance)
     - [MinDistance](https://robloxapi.github.io/ref/class/Sound.html#member-MinDistance)
     - [Pitch](https://robloxapi.github.io/ref/class/Sound.html#member-Pitch)
     - [isPlaying](https://robloxapi.github.io/ref/class/Sound.html#member-isPlaying)

- [StarterGui.ResetPlayerGuiOnSpawn](https://robloxapi.github.io/ref/class/StarterGui.html#member-ResetPlayerGuiOnSpawn)

- [Studio.UI Theme](https://robloxapi.github.io/ref/class/Studio.html#member-UI%2520Theme)

### T
- Team
     - [AutoColorCharacters](https://robloxapi.github.io/ref/class/Team.html#member-AutoColorCharacters)
     - [Score](https://robloxapi.github.io/ref/class/Team.html#member-Score)

- [TeleportService.CustomizedTeleportUI](https://robloxapi.github.io/ref/class/TeleportService.html#member-CustomizedTeleportUI)

- [Terrain.IsSmooth](https://robloxapi.github.io/ref/class/Terrain.html#member-IsSmooth)

- [TerrainRegion.IsSmooth](https://robloxapi.github.io/ref/class/TerrainRegion.html#member-IsSmooth)

- TextBox
     - [FontSize](https://robloxapi.github.io/ref/class/TextBox.html#member-FontSize)
     - [TextColor](https://robloxapi.github.io/ref/class/TextBox.html#member-TextColor)
     - [TextWrap](https://robloxapi.github.io/ref/class/TextBox.html#member-TextWrap)

- TextLabel
     - [FontSize](https://robloxapi.github.io/ref/class/TextLabel.html#member-FontSize)
     - [TextWrap](https://robloxapi.github.io/ref/class/TextLabel.html#member-TextWrap)

- [TorsionSpringConstraint.LimitEnabled](https://robloxapi.github.io/ref/class/TorsionSpringConstraint.html#member-LimitEnabled)

### U
- UserInputService
     - [ModalEnabled](https://robloxapi.github.io/ref/class/UserInputService.html#member-ModalEnabled)
     - [UserHeadCFrame](https://robloxapi.github.io/ref/class/UserInputService.html#member-UserHeadCFrame)

### V
- [VoiceChatInternal.VoiceChatState](https://robloxapi.github.io/ref/class/VoiceChatInternal.html#member-VoiceChatState)

### W
- [Workspace.FilteringEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#FilteringEnabled)

***
### Note: This list is subject to change when more things deprecate in the future.

#### If there's anything I missed or anything I made a mistake on, please let me know and I'll update it immediately.

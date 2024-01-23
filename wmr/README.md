# WMR Controller Bindings

## LC Controls

|      Action      | PC               | VR                | Notes                                                             |
| :--------------: | ---------------- | ----------------- | ----------------------------------------------------------------- |
|       Look       | Mouse Movement   | HMD               | Will use right joystick X for snap-turning                        |
|       Move       | WASD, Arrow Keys | Left Joystick     |                                                                   |
|       Jump       | Space            | Right D-pad       |                                                                   |
|      Sprint      | Shift            | (Disabled)        | Taken over by the mod, check `VR Inputs` below                    |
|     OpenMenu     | Escape, Tab      | L Menu Button     |                                                                   |
|     Interact     | E                | (Disabled)        | Taken over by the mod, check `VR Inputs` below                    |
|      Crouch      | Ctrl             | R Joystick Click  |                                                                   |
|       Use        | LMB              | Right trigger     |                                                                   |
|   ActivateItem   | LMB              | Right trigger     |                                                                   |
|     Discard      | G                | Left D-pad        |                                                                   |
|    SwitchItem    | ScrollY          | Right joystick Y  |                                                                   |
| ItemSecondaryUse | Q                | L Grip Button     |                                                                   |
| ItemTertiaryUse  | E                | R Grip Button     |                                                                   |
|     PingScan     | RMB              | Left Trigger      |                                                                   |
|    BuildMode     | B                | L Grip + R Grip   | Press both buttons simultaneously to go into build mode           |
|      Delete      | X                | L + R Trigger     |                                                                   |
|  QEItemInteract  | Q, E             | (Disabled)        | Depricated since V45, Use secondary and tertiary use instead      |
|    EnableChat    | Slash            | (Disabled)        | Chat is just not something we want to do in VR                    |
|    SubmitChat    | Enter            | (Disabled)        | Chat is just not something we want to do in VR                    |
| ReloadBatteries  | R                | (Disabled)        | Building mode prop rotating. In VR this uses Pivot in `VR Inputs` |
|   InspectItem    | Z                | (Disabled)        | Only for clipboard, disabled because there's more important stuff |
|   VoiceButton    | T                | (Disabled)        | IDK arbitary push to talk is not very favorable in VR             |
|      Emote1      | 1                | (Disabled)        | Will not bother adding this into VR                               |
|      Emote2      | 2                | (Disabled)        | Will not bother adding this into VR                               |
| ConfirmBuildMode | V                | (Disabled)        | Unused in the base game                                           |
|  SetFreeCamera   | C                | (Disabled)        | Most likely a developer only cheat                                |
|    SpeedCheat    | H                | (Disabled)        | Most likely a developer only cheat                                |

## VR Controls

|    Action    | Bind              | Notes                                                                                   |
| :----------: | ----------------- | --------------------------------------------------------------------------------------- |
| Reset Height | R Menu Button     | Recalculates the offset between your headset and the floor                              |
|     Grab     | R Grip Button     | The grab and interact button for world interactables                                    |
|     Turn     | R Joystick X Axis | If you have snap/smooth turning enabled, this will determine the direction to rotate in |
|    Pivot     | R Joystick        | Spectator camera pivoting and build mode prop rotating                                  |
|    Sprint    | L Joystick Click  | Must either be held down or toggles based on the configuration that is used             |

---
tags:
  - Property
Belongs to: "[[UCharacterMovementComponent]]"
Description: If true, smoothly rotate the Character toward the Controller's desired rotation (typically Controller->ControlRotation), using RotationRate as the rate of rotation change. Overridden by OrientRotationToMovement​If bUseControllerDesiredRotation is set to true, the character's rotation will align with the controller's rotation, which usually corresponds to the rotation of the camera, driven by the player's input (either through a game controller or the mouse).
---

## Declaration

```cpp
UPROPERTY(Category="Character Movement (Rotation Settings)", EditAnywhere, BlueprintReadWrite) uint8 bUseControllerDesiredRotation:1;
```

## Example

```cpp
GetCharacterMovement()->bUseControllerDesiredRotation = false;
```
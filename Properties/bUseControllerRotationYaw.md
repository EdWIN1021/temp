---
tags:
  - Property
Belongs to: "[[APawn]]"
Description: If true, this Pawn's yaw will be updated to match the Controller's ControlRotation yaw, if controlled by a PlayerController.
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadWrite, Category=Pawn) 
uint32 bUseControllerRotationYaw:1;
```

## Example

```cpp
bUseControllerRotationYaw = false;
```


---
tags:
  - Property
Belongs to: "[[UMovementComponent]]"
Description: If true, movement will be constrained to a plane.
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadOnly, Category=PlanarMovement) 
uint8 bConstrainToPlane:1;   
```

## Example

```cpp
GetCharacterMovement()->bConstrainToPlane = true;
```
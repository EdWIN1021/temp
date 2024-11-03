---
tags:
  - Property
Belongs to: "[[UCharacterMovementComponent]]"
Getter: 
Description: The maximum ground speed when walking. Also determines maximum lateral speed when falling.
---

## Declaration

```cpp
UPROPERTY(Category="Character Movement: Walking",
	EditAnywhere,  	
	BlueprintReadWrite,  	
	meta=(ClampMin="0", UIMin="0", ForceUnits="cm/s") 
) 
float MaxWalkSpeed;
```

## Example

```cpp
GetCharacterMovement()->MaxWalkSpeed = 400.f;
```
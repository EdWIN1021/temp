---
tags:
  - Property
Belongs to: "[[UNavMovementComponent]]"
Getter: 
Description: If true and plane constraints are enabled, then the updated component will be snapped to the plane when first attached.
---

## Declaration

```cpp
UPROPERTY(
	EditAnywhere,  	
	BlueprintReadOnly,  	
	Category=PlanarMovement,  	
	meta=(editcondition=bConstrainToPlane) 
) 
uint8 bSnapToPlaneAtStart:1;
```

## Example

```cpp
GetCharacterMovement()->bSnapToPlaneAtStart = true;
```


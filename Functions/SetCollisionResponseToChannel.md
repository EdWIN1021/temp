---
tags:
  - Function
Belongs to: "[[UPrimitiveComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Changes a member of the ResponseToChannels container for this PrimitiveComponent.
Type:
---
## Declaration

```cpp
ENGINE_API virtual void SetCollisionResponseToChannel(
	ECollisionChannel Channel, 
	ECollisionResponse NewResponse);
```

## Example

```cpp
GeometryCollection->SetCollisionResponseToChannel(ECC_Camera, ECR_Ignore);
GetMesh()->SetCollisionResponseToChannel(ECC_WorldStatic, ECR_Block);
```
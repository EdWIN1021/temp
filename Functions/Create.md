---
tags:
  - Function
Belongs to: "[[UMaterialInstanceDynamic]]"
Return: 
Interface: 
Description: Create a material instance dynamic parented to the specified material. [Optional] Specify name
---

## Declaration

```cpp
static ENGINE_API UMaterialInstanceDynamic* Create( 
  class UMaterialInterface* ParentMaterial, 
  class UObject* InOuter, FName Name = NAME_None
);
```

## Example

```cpp
UMaterialInstanceDynamic* DynamicMatInst = UMaterialInstanceDynamic::Create(DissolveMaterialInstance, this);
```
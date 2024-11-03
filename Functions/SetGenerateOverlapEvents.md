---
tags:
  - Function
Belongs to:
  - "[[UPrimitiveComponent]]"
Parameter of: 
Return: 
Interface: 
Description: Modifies value returned by GetGenerateOverlapEvents()
---

## Declaration

```cpp
UFUNCTION(BlueprintSetter)
ENGINE_API void SetGenerateOverlapEvents(bool bInGenerateOverlapEvents);
```

## Example

```cpp
GetMesh()->SetGenerateOverlapEvents(true);
```


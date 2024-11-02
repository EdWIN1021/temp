---
tags:
  - Function
Belongs to: "[[AActor]]"
Parameter of: 
Return: 
Interface: 
Description:
---

## Declaration

```cpp
FORCEINLINE FVector GetActorLocation() const {   
	return TemplateGetActorLocation(ToRawPtr(RootComponent)); 
}
```

## Example

```cpp
GetActorLocation();
```
---
tags:
  - Function
Belongs to: "[[UEngine]]"
Parameter of: 
Return: 
Interface: 
Description: 
Type:
---

## Declaration

```cpp
```

## Example

```cpp
if(GEngine) {  
	FString Message = FString::Printf(TEXT("DeltaTime: %f"), DeltaTime);  
	GEngine->AddOnScreenDebugMessage(1, 60.f, FColor::Cyan, Message);
}
```


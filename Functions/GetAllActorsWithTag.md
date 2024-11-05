---
tags:
  - Function
Belongs to: "[[UGameplayStatics]]"
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(BlueprintCallable, Category="Actor",  meta=(WorldContext="WorldContextObject"))  
static ENGINE_API void GetAllActorsWithTag(const UObject* WorldContextObject, FName Tag, TArray<AActor*>& OutActors);
```

## Example

```cpp
UGameplayStatics::GetAllActorsWithTag(OwningPawn, TargetTag, ActorsWithTag);
```
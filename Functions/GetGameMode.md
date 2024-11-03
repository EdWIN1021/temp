---
tags:
  - Function
Belongs to:
  - "[[UGameplayStatics]]"
Return: 
Description: Returns the current GameModeBase or Null if it can't be retrieved, such as on the client
---

## Declaration

```cpp
UFUNCTION(BlueprintPure, Category="Game", meta=(WorldContext="WorldContextObject"))
static ENGINE_API class AGameModeBase* GetGameMode(const UObject* WorldContextObject);
```

## Example

```cpp
AAuraGameModeBase* AuraGameMode = Cast<AAuraGameModeBase>(UGameplayStatics::GetGameMode(WorldContextObject));
```
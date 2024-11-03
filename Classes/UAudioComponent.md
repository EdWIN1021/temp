---
tags:
  - Class
Derived From: 
Context of: 
Dependency of: 
Description:
---

## Declaration

```cpp
UPROPERTY()
TObjectPtr<UAudioComponent> LoopingSoundComponent;
```

## Example

```cpp
LoopingSoundComponent = UGameplayStatics::SpawnSoundAttached(LoopingSound, GetRootComponent());
```
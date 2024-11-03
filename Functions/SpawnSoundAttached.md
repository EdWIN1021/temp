---
tags:
  - Function
Belongs to:
  - "[[UGameplayStatics]]"
Return: 
Description:
---

## Declaration

```cpp
UFUNCTION(
  BlueprintCallable, 
  Category="Audio", 
  meta=(AdvancedDisplay = "2", UnsafeDuringActorConstruction = "true", Keywords = "play"))
static ENGINE_API UAudioComponent* SpawnSoundAttached(
  USoundBase* Sound, 
  USceneComponent* AttachToComponent, 
  FName AttachPointName = NAME_None, 
  FVector Location = FVector(ForceInit), 
  FRotator Rotation = FRotator::ZeroRotator, 
  EAttachLocation::Type LocationType = EAttachLocation::KeepRelativeOffset, 
  bool bStopWhenAttachedToDestroyed = false, 
  float VolumeMultiplier = 1.f, 
  float PitchMultiplier = 1.f, 
  float StartTime = 0.f, 
  USoundAttenuation* AttenuationSettings = nullptr, 
  USoundConcurrency* ConcurrencySettings = nullptr, 
  bool bAutoDestroy = true);

```

## Example

```cpp
LoopingSoundComponent = UGameplayStatics::SpawnSoundAttached(LoopingSound, GetRootComponent());
```
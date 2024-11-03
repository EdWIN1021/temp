---
tags:
  - Function/Blueprint
Belongs to: "[[UGameplayStatics]]"
Parameter of: 
Return: 
Interface: 
Description:
---
## Declaration

```cpp
UFUNCTION(
  BlueprintCallable, 
  Category="Audio", 
  meta=(
    WorldContext="WorldContextObject", 
    AdvancedDisplay = "3", 
    UnsafeDuringActorConstruction = "true", 
    Keywords = "play"
  )
)
static ENGINE_API void PlaySoundAtLocation(
  const UObject* WorldContextObject, 
  USoundBase* Sound, 
  FVector Location, 
  FRotator Rotation, 
  float VolumeMultiplier = 1.f, 
  float PitchMultiplier = 1.f, 
  float StartTime = 0.f, 
  class USoundAttenuation* AttenuationSettings = nullptr, 
  USoundConcurrency* ConcurrencySettings = nullptr, 
  const AActor* OwningActor = nullptr, 
  const UInitialActiveSoundParams* InitialParams = nullptr
);

```

## Example

```cpp
UGameplayStatics::PlaySoundAtLocation(
  this, 
  ImpactSound, 
  GetActorLocation(), 
  FRotator::ZeroRotator
);
```

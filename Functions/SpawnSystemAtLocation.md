---
tags:
  - Function
Belongs to:
  - "[[UNiagaraFunctionLibrary]]"
Return: 
Interface: 
Description: Spawns a Niagara System at the specified world location/rotation
---

## Declaration

```cpp
UFUNCTION(
  BlueprintCallable, 
  Category = Niagara, 
  meta = (
    Keywords = "niagara System", 
    WorldContext = "WorldContextObject", 
    UnsafeDuringActorConstruction = "true"
  )
)
static NIAGARA_API UNiagaraComponent* SpawnSystemAtLocation(
  const UObject* WorldContextObject, 
  class UNiagaraSystem* SystemTemplate, 
  FVector Location, 
  FRotator Rotation = FRotator::ZeroRotator, 
  FVector Scale = FVector(1.f), 
  bool bAutoDestroy = true, 
  bool bAutoActivate = true, 
  ENCPoolMethod PoolingMethod = ENCPoolMethod::None, 
  bool bPreCullCheck = true
);
```

## Example

```cpp
UNiagaraFunctionLibrary::SpawnSystemAtLocation(this, ImpactEffect, GetActorLocation());
```
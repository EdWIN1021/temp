---
tags:
  - Class
Belongs to: 
Initialization: 
Has: 
Declaration: 
Description:
---

## Declaration

```cpp
#pragma once  
  
#include "GameplayEffectTypes.h"  
#include "AuraAbilityTypes.generated.h"  
  
USTRUCT(BlueprintType)  
struct FAuraGameplayEffectContext : public FGameplayEffectContext  
{  
    GENERATED_BODY();  
  
public:  
    bool IsCriticalHit() const { return bIsCriticalHit; };  
    bool IsBlockHit() const { return bIsBlockHit; };  
  
    void SetIsCriticalHit(bool bInIsCriticalHit) { bIsCriticalHit = bInIsCriticalHit; };  
    void SetIsBlockHit(bool bInIsBlockHit) { bIsBlockHit = bInIsBlockHit; };  
  
    virtual UScriptStruct* GetScriptStruct() const override  
    {  
       return FGameplayEffectContext::StaticStruct();  
    }  
    virtual bool NetSerialize(FArchive& Ar, UPackageMap* Map, bool& bOutSuccess);  
  
protected:  
    UPROPERTY()  
    bool bIsBlockHit = false;  
    UPROPERTY()  
    bool bIsCriticalHit = false;  
};

```

## Example

```cpp

```

## Getter

```cpp
```

## Options
- 
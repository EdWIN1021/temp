---
tags:
  - Class
Belongs to: 
Initialization: []
Has: 
Declaration: 
Description:
---

## Declaration

```cpp
UPROPERTY(VisibleAnywhere, BlueprintReadOnly, Category = "Collision") 
UBoxComponent* BoxCollisionComponent;
```

## Example

```cpp
BoxCollisionComponent = CreateDefaultSubobject<UBoxComponent(TEXT("BoxCollisionComponent"));
```

## Getter

```cpp
// Fill out your copyright notice in the Description page of Project Settings.  
  
  
#include "AbilitySystem/ExecCalc/ExecCalc_Damage.h"  
#include "AbilitySystemComponent.h"  
#include "AuraAbilityTypes.h"  
#include "AuraGameplayTags.h"  
#include "AbilitySystem/AuraAbilitySystemLibrary.h"  
#include "AbilitySystem/AuraAttributeSet.h"  
#include "AbilitySystem/Data/CharacterClassInfo.h"  
#include "Interaction/CombatInterface.h"  
  
struct AuraDamageStatics  
{  
    DECLARE_ATTRIBUTE_CAPTUREDEF(Armor);  
    DECLARE_ATTRIBUTE_CAPTUREDEF(ArmorPenetration);  
    DECLARE_ATTRIBUTE_CAPTUREDEF(BlockChance);  
    DECLARE_ATTRIBUTE_CAPTUREDEF(CriticalHitChance);  
    DECLARE_ATTRIBUTE_CAPTUREDEF(CriticalHitResistance);  
    DECLARE_ATTRIBUTE_CAPTUREDEF(CriticalHitDamage);  
    AuraDamageStatics()  
    {       
       DEFINE_ATTRIBUTE_CAPTUREDEF(UAuraAttributeSet, BlockChance, Target, false);  
       DEFINE_ATTRIBUTE_CAPTUREDEF(UAuraAttributeSet, ArmorPenetration, Source, false);  
       DEFINE_ATTRIBUTE_CAPTUREDEF(UAuraAttributeSet, CriticalHitChance, Source, false);  
       DEFINE_ATTRIBUTE_CAPTUREDEF(UAuraAttributeSet, CriticalHitResistance, Target, false);  
       DEFINE_ATTRIBUTE_CAPTUREDEF(UAuraAttributeSet, CriticalHitDamage, Source, false);  
    }};  
  
static const AuraDamageStatics& DamageStatics()  
{  
    static AuraDamageStatics DStatics;  
    return DStatics;  
}  
```

## Options
- 
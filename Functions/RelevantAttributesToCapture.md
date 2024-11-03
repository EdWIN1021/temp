---
tags:
  - Function
Belongs to: "[[UGameplayEffectCalculation]]"
Return: 
Interface: 
Description: Attributes to capture that are relevant to the calculation
---

## Declaration

```cpp
UPROPERTY(EditDefaultsOnly, BlueprintReadOnly, Category=Attributes)
TArray<FGameplayEffectAttributeCaptureDefinition> RelevantAttributesToCapture;
```

## Example

```cpp
RelevantAttributesToCapture.Add(DamageStatics().ArmorDef);
```
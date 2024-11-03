---
tags:
  - Macro
Description: 
Belongs to:
  - "[[UGameplayEffectExecutionCalculation]]"
---

## Declaration

```cpp
#define DEFINE_ATTRIBUTE_CAPTUREDEF(S, P, T, B) \
{ \
	P##Property = FindFieldChecked<FProperty>(S::StaticClass(), GET_MEMBER_NAME_CHECKED(S, P)); \
	P##Def = FGameplayEffectAttributeCaptureDefinition(P##Property, EGameplayEffectAttributeCaptureSource::T, B); \
}

```

## Example

```cpp
```

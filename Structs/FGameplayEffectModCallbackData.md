---
tags:
  - Struct
Description: 
Properties:
  - "[[FGameplayEffectSpec]]"
  - "[[UAbilitySystemComponent]]"
  - "[[FGameplayModifierEvaluatedData]]"
Class:
---

## Declaration

```cpp
struct FGameplayEffectModCallbackData
{
	FGameplayEffectModCallbackData(const FGameplayEffectSpec& InEffectSpec, FGameplayModifierEvaluatedData& InEvaluatedData, UAbilitySystemComponent& InTarget)
		: EffectSpec(InEffectSpec)
		, EvaluatedData(InEvaluatedData)
		, Target(InTarget)
	{
	}

	const struct FGameplayEffectSpec&		EffectSpec;		// The spec that the mod came from
	struct FGameplayModifierEvaluatedData&	EvaluatedData;	// The 'flat'/computed data to be applied to the target

	class UAbilitySystemComponent &Target;		// Target we intend to apply to
};
```

## Example

```cpp
```

## Options
- 
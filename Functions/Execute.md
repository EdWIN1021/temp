---
tags:
  - Function
Belongs to: "[[UGameplayEffectExecutionCalculation]]"
Parameter of: 
Return: 
Interface: 
Description: UGameplayEffectExecutionCalculation
---
## Declaration

```cpp
UFUNCTION(BlueprintNativeEvent, Category="Calculation")
void Execute(
  const FGameplayEffectCustomExecutionParameters& ExecutionParams, 
  FGameplayEffectCustomExecutionOutput& OutExecutionOutput
) const;
```

## Example

```cpp
void UExecCalc_Damage::Execute_Implementation(const FGameplayEffectCustomExecutionParameters& ExecutionParams,
                                              FGameplayEffectCustomExecutionOutput& OutExecutionOutput) const
{
	const UAbilitySystemComponent* SourceASC = ExecutionParams.GetSourceAbilitySystemComponent();
	const UAbilitySystemComponent* TargetASC = ExecutionParams.GetTargetAbilitySystemComponent();

	const AActor* SourceAvatar = SourceASC ? SourceASC->GetAvatarActor() : nullptr;
	const AActor* TargetAvatar = SourceASC ? TargetASC->GetAvatarActor() : nullptr;

	const FGameplayEffectSpec& Spec = ExecutionParams.GetOwningSpec();
}
```
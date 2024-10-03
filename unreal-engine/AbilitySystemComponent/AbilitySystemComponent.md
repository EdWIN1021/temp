---
tags:
  - "#CharacterMovement"
  - blueprint
Base: "[[AddMovementInput]]"
jj: "#xsdxsdx"
---
#sxsxsx



![[unreal-engine/AbilitySystemComponent/screenshot_01.png]]
```cpp
PROPERTY()  
TObjectPtr<UAbilitySystemComponent> AbilitySystemComponent;
```

```cpp title:constructor
AbilitySystemComponent = CreateDefaultSubobject<UAuraAbilitySystemComponent>(TEXT("AbilitySystemComponent"));
```

[[AddMovementInput]]

![[AddMovementInput#^bba9a8]]
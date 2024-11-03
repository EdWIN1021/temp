---
tags:
  - Property
Struct: "[[FActorTickFunction]]"
Belongs to: 
Getter: 
Description: If false, this tick function will never be registered and will never tick. Only settable in defaults
---

## Declaration

```cpp
UPROPERTY() 
uint8 bCanEverTick:1;
```

## Example

```cpp
PrimaryActorTick.bCanEverTick = false
```
---
tags:
  - Property
Belongs to: "[[APlayerController]]"
Getter: 
Description: Type of mouse cursor to show by default
---

## Declaration

```cpp
UPROPERTY(EditAnywhere, BlueprintReadOnly, Category=MouseInterface) TEnumAsByte<EMouseCursor::Type> DefaultMouseCursor;
```

## Example

```cpp
DefaultMouseCursor = EMouseCursor::Default;
```


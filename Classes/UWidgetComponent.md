---
tags:
  - Class
Belongs to:
  - "[[UMeshComponent]]"
Initialization: 
Has: 
Declaration: 
Description:
---

## Declaration

```cpp
UPROPERTY(VisibleAnywhere, BlueprintReadOnly)
TObjectPtr<UWidgetComponent> HealthBar;
```

## Example

```cpp
UAuraUserWidget* AuraUserWidget = Cast<UAuraUserWidget>(HealthBar->GetUserWidgetObject())
```

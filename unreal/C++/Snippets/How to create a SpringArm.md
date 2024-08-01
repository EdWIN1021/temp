```cpp
//.h
class USpringArmComponent;

UPROPERTY(VisibleAnywhere)
USpringArmComponent* CameraBoom;

//.cpp
#include "Components/SpringArmComponent.h"
CameraBoom = CreateDefaultSubobject<USpringArmComponent>(TEXT("SpringArm"));
CameraBoom->SetupAttatchment(GetRootComponent());
CameraBoom->TargetArmLength = 300.f;
```
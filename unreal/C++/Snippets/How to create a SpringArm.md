```cpp
//.h
class USpringArmComponent;
USpringArmComponent* SpringArm;

//.cpp
#include "Components/SpringArmComponent.h"
SpingArm = CreateDefaultSubobject<USpringArmComponent>(TEXT("SpringArm"));
SpringArm->SetupAttatchment(GetRootComponent());
SpringArm->TargetArmLength = 300.f;
```
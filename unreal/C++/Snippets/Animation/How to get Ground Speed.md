```cpp
//.h
UPROPERTY(BlueprintReadOnly, Category = "Movement")
float GroundSpeed;
```



```cpp
//.cpp
#include "Kismet/KismetMathLibrary.h"

void USlashAnimInstance::NativeUpdateAnimation(float DeltaTime)
{
	Super::NativeUpdateAnimation(DeltaTime);

	if(SlashCharacterMovement){
		GroundSpeed = UKismetMathLibrary::VSizeXY(SlashCharacterMovement->Velocity);
	}
}
```
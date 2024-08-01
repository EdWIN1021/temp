```cpp
//.h
UPROPERTY(BlueprintReadOnly, Category = "Movement")
class ASlashCharacter* SlashCharacter;

UPROPERTY(BlueprintReadOnly, Category = "Movement")
class UCharacterMovementComponent* SlashCharacterMovement;
```

```cpp
//.cpp
#include "GameFramework/CharacterMovementComponent.h"

void USlashAnimInstance::NativeInitializeAnimation()
{
	Super::NativeInitializeAnimation();

	SlashCharacter = Cast<ASlashCharacter>(TryGetPawnOwner());
	if(SlashCharacter)
	{
		SlashCharacterMovement = SlashCharacter->GetCharacterMovement();
	}
}
```
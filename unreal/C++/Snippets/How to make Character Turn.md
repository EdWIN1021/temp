Project Setting -> Input -> Action Mappings -> Axis Mappings
![[Screenshot 2024-07-31 at 7.26.51 PM.png]]


```cpp
//.h
protected:
  void Turn(float Value);

//.cpp
void ASlashCharacter::Turn(float Value){
	AddControllerYawInput(Value);
}

void ASlashCharacter::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent){
	Super::SetupPlayerInputComponent(PlayerInputComponent);
	PlayerInputComponent->BindAxis(FName("Turn"), this, &ASlashCharacter::Turn);
}

```
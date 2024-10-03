Project Setting -> Input -> Action Mappings -> Axis Mappings
![[Screenshot 2024-07-31 at 7.05.52 PM.png]]

```cpp
//.h
protected:
  void MoveRight(float Value);

//.cpp
void ASlashCharacter::MoveRight(float Value) {
	if (Controller && Value != 0.f){
	
	const FRotator ControlRotation = GetControlRotation();
	
	const FRotator YawRotation(0.f, ControlRotation.Yaw, 0.f);
	
	const FVector Direction = FRotationMatrix(YawRotation).GetUnitAxis(EAxis::Y);
	
	AddMovementInput(Direction, Value);
	
	}
}

void ASlashCharacter::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent){
	Super::SetupPlayerInputComponent(PlayerInputComponent);
	PlayerInputComponent->BindAxis(FName("MoveRight"), this, &ASlashCharacter::MoveRight);
}

```
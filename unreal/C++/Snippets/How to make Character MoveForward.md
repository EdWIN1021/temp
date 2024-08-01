Project Setting -> Input -> Action Mappings -> Axis Mappings
![[Screenshot 2024-07-31 at 7.18.57 PM.png]]

```cpp
//.h
protected:
  void MoveForward(float Value);

//.cpp
void ASlashCharacter::MoveForward(float Value) {
	if (Controller && Value != 0.f) {
		// Get the rotation of the controller
		const FRotator ControlRotation = GetControlRotation();
		
		// Create a rotator with only the yaw component (ignores pitch and roll)
		const FRotator YawRotation(0.f, ControlRotation.Yaw, 0.f);
		
		// Get the forward direction vector from the yaw rotation
		const FVector Direction = FRotationMatrix(YawRotation).GetUnitAxis(EAxis::X);
		
		// Apply the movement input in the forward direction
		AddMovementInput(Direction, Value);
	}
}

void ASlashCharacter::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent){
	Super::SetupPlayerInputComponent(PlayerInputComponent);
	PlayerInputComponent->BindAxis(FName("MoveForward"), this, &ASlashCharacter::MoveForward);
}

```
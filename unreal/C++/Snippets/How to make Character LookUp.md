Project Setting -> Input -> Action Mappings -> Axis Mappings
![[Screenshot 2024-07-31 at 7.23.52 PM.png]]

```cpp
//.h
protected:
  void LookUp(float Value);

//.cpp
void ASlashCharacter::LookUp(float Value){
	AddControllerPitchInput(Value);
}

void ASlashCharacter::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent){
	Super::SetupPlayerInputComponent(PlayerInputComponent);
	PlayerInputComponent->BindAxis(FName("LookUp"), this, &ASlashCharacter::LookUp);
}

```
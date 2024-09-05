## Jump

```cpp
PlayerInputComponent->BindAction(FName("Jump"), IE_Pressed, this, &ACharacter::Jump);
```

## Look Up
```cpp
PlayerInputComponent->BindAxis(FName("LookUp"), this, &ASlashCharacter::LookUp);
```
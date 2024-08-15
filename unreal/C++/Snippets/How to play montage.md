```cpp
//.h
class UAnimMontage;

UPROPERTY(EditDefaultsOnly, Category = "Montages")  
UAnimMontage* EquipMontage;
```

```cpp
//.cpp
void ASlashCharacter::PlayEquipMontage(FName SectionName)  
{  
    UAnimInstance* AnimInstance = GetMesh()->GetAnimInstance();  
  
    if (AnimInstance && EquipMontage)  
    {  
       AnimInstance->Montage_Play(EquipMontage);  
       AnimInstance->Montage_JumpToSection(SectionName, EquipMontage);  
    }  
}
```

BP
![[Screenshot 2024-08-09 at 11.04.37 AM.png]]
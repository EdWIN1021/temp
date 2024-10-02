#UAbilitySystemComponent 

```cpp
virtual void InitAbilityActorInfo(AActor* InOwnerActor, AActor* InAvatarActor)
```

```cpp
void A<Character>::BeginPlay()  
{  
    Super::BeginPlay();  
    AbilitySystemComponent->InitAbilityActorInfo(this, this);  
}
```



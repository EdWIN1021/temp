![[unreal-engine/AttributeSet/screenshot_01.png]]

```cpp
UPROPERTY()  
TObjectPtr<UAttributeSet> AttributeSet;

AttributeSet = CreateDefaultSubobject<UAuraAttributeSet>("AttributeSet");
```


## Getter

^83abb4

```cpp
UAttributeSet* GetAttributeSet() const { return AttributeSet; };
```

^ff00cc


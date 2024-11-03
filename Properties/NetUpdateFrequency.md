---
tags:
  - Property
Belongs to: "[[AActor]]"
Getter: 
Description: How often (per second) this actor will be considered for replication, used to determine NetUpdateTime
---

## Declaration

```cpp
UPROPERTY(Category=Replication, EditDefaultsOnly, BlueprintReadWrite)
float NetUpdateFrequency;
```

## Example

```cpp
NetUpdateFrequency = 100.f;
```
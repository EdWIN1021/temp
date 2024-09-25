- GAMEPLAYATTRIBUTE_REPNOTIFY macro handles <font color="#c0504d">notifying other systems</font> (like UI or gameplay logic) that the attribute has changed, allowing for appropriate updates.

```cpp
GAMEPLAYATTRIBUTE_REPNOTIFY(UAuraAttributeSet, Health, OldHealth);
```
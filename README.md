# csarchFinal

## Q2

modifed:
+ gem5/configs/common/Caches.py
+ gem5/configs/common/CacheConfig.py
+ gem5/configs/common/Options.py
+ gem5/src/cpu/BaseCPU.py
+ gem5/src/mem/XBar.py

## Q3

```
l3_assoc = ?
```

## Q4

modifed:
+ gem5/src/mem/cache/replacement_policies/lfu_rp.cc

## Q5

modifed:
+ gem5/src/mem/cache/base.cc

在 access 底下，有 writable 的就直接寫回去

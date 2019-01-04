# kernel_objects

Information about kernel objects from different kernels collected in one place.

### Android kernels

#### Samsung Galaxy S8
```
dream2lte:/ $ cat /proc/slabinfo | grep kmalloc                                                                                                                                                                      
kmalloc-8192         209    224   8192    4    8 : tunables    0    0    0 : slabdata     56     56      0
kmalloc-4096         411    440   4096    8    8 : tunables    0    0    0 : slabdata     55     55      0
kmalloc-2048         706    752   2048   16    8 : tunables    0    0    0 : slabdata     47     47      0
kmalloc-1024        2594   5568   1024   32    8 : tunables    0    0    0 : slabdata    174    174      0
kmalloc-512         4048   4192    512   32    4 : tunables    0    0    0 : slabdata    131    131      0
kmalloc-256        22017  24384    256   32    2 : tunables    0    0    0 : slabdata    762    762      0
kmalloc-128       121556 129408    128   32    1 : tunables    0    0    0 : slabdata   4044   4044      0

```
#### Samsung Galaxy S9

* <a href="Samsung Galaxy/exynos/G960FXXU2CRLI">G960FXXU2CRLI</a>

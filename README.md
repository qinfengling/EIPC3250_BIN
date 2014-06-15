EIPC3250_BIN
============

EIPC3250 PartionTable

| PartionName  | Scope(block begin to end)  | Size(block numbers) |
| :------------ |:---------------:| -----:|
| ks      | 0 | 1 |
| s1l      | 1-25        |   24 |
| uboot | 25- 90       |    65 |
| uboot param | 90-100        |    10 |
| kernel | 100-356        |    256 |
| rootfs | 356-end        |    ref flash datasheet |

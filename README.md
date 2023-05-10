# AHNU座位预约脚本
> 使用Python完成图书馆自动预约座位（安徽师范大学（花津校区）敬文图书馆)
> **2023年5月10日完成。**

### 由于github上的图片显示有问题，所以操作指南放在gitee上
```angular2html
https://gitee.com/liuliuliuyuyuy/ahnulibrary-operation-guide
```

### 特别说明
1. 项目在此项目的基础上开发```  https://github.com/yangchnet/AHNUReserve  ```
2. 具体变化
> * 修改邮箱推送为微信推送
> * 增加了预约楼层，具体增加了图书馆2楼，图书馆3、4楼公共空间的座位（以前只可预约3、4楼的部分位置）
> * 修改了当该预约位置冲突时，无法预约下一个位置的BUG，本项目如果所预约位置与他人有冲突，会自动预约编号的下一个位置
> * 请注意上文的编号不是nskxxxx的编号，而是座位信息在传输中的编号，由于图书馆座位编号有些小小的混乱，所以可能会让预约位置和设置位置离得比较远，请在微信中及时查看

### 最后
**有用请给个STAR，欢迎Fork** 

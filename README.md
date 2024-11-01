## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Oct 23 03:17:12 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 01:16:39 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 01:17:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 01:15:03 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 01:22:15 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 01:19:50 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 01:18:27 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 01:17:34 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 01:18:17 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 01:22:48 UTC 2024

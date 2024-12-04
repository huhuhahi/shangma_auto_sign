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
- Auto Sign-in run successful on Sat Nov  2 01:15:45 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 01:22:02 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 01:19:02 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 01:15:26 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 01:15:19 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 01:15:44 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 01:15:39 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 01:13:46 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 01:20:11 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 01:17:14 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 01:14:55 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 01:16:24 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 01:16:25 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 01:21:04 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 01:19:22 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 01:24:49 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 01:22:09 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 01:20:54 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 01:20:06 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 01:20:06 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 01:21:07 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 01:17:54 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 01:25:22 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 01:22:07 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 01:21:15 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 01:22:40 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 01:22:15 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 01:22:09 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 01:20:17 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 01:42:13 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 01:24:53 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 01:23:43 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 01:23:57 UTC 2024

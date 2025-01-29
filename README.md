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
- Auto Sign-in run successful on Thu Dec  5 01:23:54 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 01:22:59 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 01:22:28 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 01:36:32 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 01:25:51 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 01:24:53 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 01:23:55 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 01:23:14 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 01:24:40 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 01:21:07 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 01:36:21 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 01:26:15 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 01:23:28 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 01:20:19 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 01:21:09 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 01:17:22 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 01:15:54 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 01:22:53 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 01:18:27 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 01:17:01 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 01:16:08 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 01:16:17 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 01:16:41 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 01:15:24 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 01:23:39 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 01:19:07 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 01:16:34 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 01:23:03 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 01:16:07 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 01:17:09 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 01:15:36 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 01:22:46 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 01:20:20 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 01:17:32 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 01:17:27 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 01:16:50 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 01:19:07 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 01:17:35 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 01:24:07 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 01:20:56 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 01:13:47 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 01:15:37 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 01:14:52 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 01:14:36 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 01:12:51 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 01:20:23 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 01:16:11 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 01:14:45 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 01:16:44 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 01:15:06 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 01:15:21 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 01:11:50 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 01:17:29 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 01:16:25 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 01:14:57 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 01:15:03 UTC 2025

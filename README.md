# 弹弹追鸡 Bounce Flock

抖音 / TikTok 风格的摄像头特效小游戏。转动脑袋移动，张嘴触发动作。像素风 3D，支持 2–5 人联网对战。

- `index.html`：联机 PvP 版。一人当老鹰，其他人当小鸡，抢「?」盒子变身肌肉男小鸡
- `solo.html`：单人 30 秒版

技术：three.js（低分辨率像素渲染）· MediaPipe Face Landmarker（人脸识别，只在本机运行）· PeerJS（房间号联机）· MediaRecorder（内置录屏）

手机需要用 https 打开才能使用摄像头。不开摄像头也能玩：手指拖动移动，右下按钮跳。

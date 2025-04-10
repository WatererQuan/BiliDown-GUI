# BilibiliDownloaderGUI 一个有简洁操作界面的哔哩哔哩视频下载器~

## 📌 软件定位
基于Python开发的Windows桌面工具，支持B站视频多格式下载，**仅供学习研究使用**

## 🛠️ 主要功能
- 支持BV号/视频链接解析
- 多画质下载（最高支持4K大会员专享）
- 分P视频选择下载
- 扫码登录账号系统
- 音视频分离下载与合并
- 封面下载（字幕功能开发中）

## 🚀 快速开始
### 方法一：直接运行exe
1. 从[Releases页面](#)下载最新版`Bilibili_downloader_gui.exe`
2. 双击直接运行，无需安装任何依赖

### 方法二：源码运行
```bash
# 克隆仓库
git clone https://github.com/yourname/bilibilidown.git

# 安装依赖
pip install -r requirements.txt

# 启动程序
python bilibili_downloader_gui.py
```

## 📖 使用指南
1. 输入视频链接 粘贴BV号（如 BV1xx411x7xx ）或完整视频链接
2. 设置下载选项
   
   - 画质选择（需对应等级账号权限）
   - 存储路径设置（默认：用户下载目录）
   - 分P选择（多章节视频）
3. 登录账号（可选） 点击右上角扫码登录获取大会员权限
4. 开始下载
   
   - 支持暂停/继续/取消操作
   - 实时显示下载进度和速度

## ⚙️ 技术原理
1. B站API调用 - 通过逆向分析获取视频流信息
2. 多线程下载 - 实现高速分块下载和进度监控
3. FFmpeg整合 - 完成音视频合并（需ffmpeg.exe）
4. Cookie持久化 - 采用本地加密存储登录状态
## ❓ 常见问题
### 登录失败
1. 检查系统时间是否准确
2. 删除 APPDATA/BiliDown 目录后重试
3. 确保使用最新版B站客户端扫码
### 下载速度慢
1. 切换下载接口尝试
2. 检查网络连接状态
3. 避免同时下载多个视频
### 视频无法播放
1. 确保已安装 FFmpeg
2. 检查视频文件完整性
3. 尝试重新合并音视频
## ⚠️ 免责声明
本工具仅限用于个人学习研究，严禁任何商业用途！

使用者应确保遵守《中华人民共和国网络安全法》《信息网络传播权保护条例》等相关法律法规。开发者不承担因使用本工具导致的任何法律责任，包括但不限于：

- 侵犯版权导致的民事/刑事责任
- 账号封禁等B站官方处罚
- 数据泄露等安全问题
## 📜 版权声明
- 本软件使用Python开发，界面设计由Trae AI辅助完成
- 视频版权归属哔哩哔哩及原创作者所有
- 用户cookies信息仅加密存储于本地
- 核心代码采用GPL-3.0协议开源
📧 反馈邮箱： watererquan@outlook.com


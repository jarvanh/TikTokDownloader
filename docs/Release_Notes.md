**更新内容：**

1. default_mode 参数变更为 run_command 参数
2. 修复 TikTok 直播推流地址不显示的问题
3. 修复未输入收藏合集序号报错的问题
4. 修复从文本文档读取链接异常的问题
5. 使用 rookiepy 替代 browser-cookie3
6. 修复调用 FFmpeg 下载直播功能
7. 优化从浏览器读取 Cookie 功能
8. 支持更多 TikTok 合辑链接格式
9. 支持最高分辨率视频文件下载
10. 修复代理参数测试报错的问题
11. 修复作品文件响应为空的问题
12. 优化 run_command 参数功能
13. 新增实况/动图作品下载功能
14. 恢复作品评论数据采集功能
15. 恢复账号详细数据采集功能
16. 优化作品文件名称处理逻辑
17. 优化文件名称非法字符处理
18. 重构视频下载地址提取逻辑
19. 优化 earliest 参数设置规则
20. 适配最新版 FFmpeg 命令
21. 日志不再记录请求体数据
22. 捕获中断程序的异常错误
23. 优化重定向链接获取逻辑
24. 更新 proxy 参数设置规则
25. 优化检查版本更新功能
26. 优化请求参数编码处理
27. 优化音乐文件格式判断
28. 新增文件断点续传功能
29. 修复删除下载记录功能
30. 捕获响应码异常的错误
31. 优化文件名称长度限制
32. 优化程序运行状态提示
33. 更新网络接口请求参数
34. 适配新版本 HTTPX 库
35. 移除直播内置下载器
36. 新增英语语言支持
37. 优化文件下载功能
38. 优化代理测试逻辑
39. 修复其他已知问题
40. 优化代码运行逻辑

<p><strong>注意：<code>5.5</code> 版本的配置文件与旧版本配置文件不兼容；旧版本程序更新后，建议重命名旧版本配置文件，然后运行程序生成默认配置文件，手动迁移配置文件内容；不兼容的参数：<code>browser_info</code>、<code>browser_info_tiktok</code>，其余参数无需处理！</strong></p>

<p><strong>Windows 系统需要以管理员身份运行程序才能读取 Chromium、Chrome、Edge 浏览器 Cookie！</strong></p>

<p><strong>注意：Mac OS 平台可执行文件 <code>main</code> 可能需要从终端命令行启动；受设备限制，Mac OS 平台可执行文件尚未经过测试，无法保证可用性！</strong></p>

物历 Web 重置版 0.1

为什么改成 Web/PWA：
Swift Playground 4.7 在 iPadOS 27 上存在文字输入兼容问题。此版本直接运行在 Safari/WebKit，不依赖 Swift Playground 的 App 运行容器。

功能：
- 物品照片卡片
- 名称、品牌/型号、分类、状态、购入日期、价格、位置、备注
- 每件物品独立时间线
- 搜索、归档
- IndexedDB 本机保存
- JSON 导出/导入
- PWA 离线缓存

要像 App 一样装到 iPhone/iPad 主屏幕：
需把整个文件夹放在 HTTPS 静态网站上，然后 Safari 打开 -> 分享 -> 添加到主屏幕。

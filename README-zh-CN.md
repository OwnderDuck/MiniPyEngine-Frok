# MiniPyEngine
## 🌐 请选择语言 简体中文 | [English](README.md)
**MiniPyEngine** 是对 Alexander Freyr Lúðvíksson 于 2023 年创作的游戏引擎进行了大幅改进和重构后的版本。

该版本由 **Ege** 于 2025 年遵循 MIT 许可证开发和扩展。

---

## 特性：
- 使用 .obj 和 .mtl 文件加载模型和纹理（不支持 .glb 格式）
- 支持多人联机

**支持多种分辨率，包括**
- VGA (`640×480 像素`)
- SVGA (`800×600 像素`)
- HD (`720p, 1280×720 像素`)
- Full HD (`1080p, 1920×1080 像素`)
- 2K (`QHD / WQHD, 2560×1440 像素`)
- 4K (`UHD, 3840×2160 像素`) 

## MiniPyEngine 的改变与改进
- 修复了原始代码中的大量漏洞
- 默认添加了全屏模式
- 创建了全新的更人性化的主菜单
- 修复了自由视角（鼠标控制视角）系统的问题
- ...

---

## 已知 Bugs:
- 暂无
  
---

## 怎么玩？（默认 Player.py）
- 用 `WASD` 控制角色移动
- 按住 `Shift` 奔跑
- 按 `Space` 跳跃
- 按 `Ctrl` 下蹲
- 用鼠标移动视角和瞄准
- 点击左键以射击或交互
- 按 `Esc` 打开暂停菜单

---

## 如何启动游戏？

- 双击 `main.py`
- 点击 **Settings button** 以进行配置检查. 
- 若无法启动程序，请用文本编辑器打开 `config` 文件并检查配置项
- 最后，运行 `StartGame.py` 启动游戏

---

## 系统要求

### 最低配置建议：
- **操作系统：** Windows 10, Linux （建议使用 Ubuntu 18.04 LTS 或更新版本）
- **Python版本：** 3.8  
- **CPU：** 双核 2.0 GHz  
- **内存：** 80 MB （游戏运行需要）
- **GPU：** 支持 OpenGL 3.3 的集成显卡
- **存储：** 20 MB
- **依赖库：** `pygame`，`PyOpenGL`，`numpy`，`shortuuid`，`psutil`

---

## 技术细节

MiniPyEngine 使用现代 OpenGL 技术以及自定义 GLSL 着色器，实现超越传统图形管线的高级图像效果。
运行时，着色器从 `shaders/` 加载并编译。
如果你想开发属于自己的游戏，只需修改 `Player.py`，添加你的`.obj`，`.mtl`，和贴图素材，并在 `objects` 文件夹中定义你的物体。





---

## 许可证

本项目遵循 `MIT` 开源许可证。

- 原引擎作者: Alexander Freyr Lúðvíksson (2023)  
- 修改与扩展: MiniPyEngine by Ege Onder (2025)

---

## 未来版本计划

MiniPyEngine 正在持续开发中。
预计将推出的新版本将包含更多功能、性能改进及辅助开发工具。（预计版本：1.1.0-S 稳定版）
计划中的新功能包括：

- 升级优化方式和性能
- 增强图形渲染系统
- 支持更多平台和分辨率
- 扩展文档和学习资源
- 支持声音
- 完善联机系统
- 支持地图文件加载
- 支持 NPC
---

如果你已经下载并使用了本项目，感谢你对 MiniPyEngine 的支持！

###### 由 @OwnderDuck 翻译，校对 Copilot, @hootime-1083

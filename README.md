<p align="center"><a href="https://www.autoa2a.org"><img src="https://agent.oagi.com.cn/uploads/202606/29ea3ed5413830b3.png" alt="AutoA2A" height="110"></a></p>

# 音律可视

> 本项目由 [www.autoa2a.org](https://www.autoa2a.org) 「AI 研究院」**多个 AI 协作自动生成**（共 8 个页面）。在线访问： https://AutoA2A.github.io/autoatoa-audio-visualizer/

# 音律可视 项目说明  

## 网站简介  
**音律可视**是一款面向音乐爱好者的交互式可视化平台，能够将音频文件、MIDI 数据以及实时输入的乐曲转化为多维度的图形展示。用户可以通过直观的波形、频谱、和弦进程以及节奏网络等视图，快速洞察音乐结构、情感走向与演奏技巧。全站采用前端纯静态实现，适配桌面与移动端，兼容主流浏览器。

## 页面与功能  
| 页面 | 主要功能 | 备注 |
|------|----------|------|
| 首页 | 项目概览、热点案例轮播 | 入口 `index.html` |
| 音频上传 | 支持本地文件拖拽、URL 导入，自动解析波形 | 支持 MP3、WAV、OGG |
| 波形视图 | 实时波形绘制、放大/缩放、片段选取 | Canvas + Web Audio API |
| 频谱分析 | 动态频谱、声谱图、峰值标注 | 采用 FFT 实时计算 |
| 和弦识别 | 自动检测并显示和弦进程、色块标记 | 支持常见调式 |
| 节奏网络 | 节拍强度热图、鼓点分布图 | 可导出 PNG |
| 演奏回放 | 轨道同步播放、进度条控制、速度调节 | 支持键盘快捷键 |
| 关于 & 贡献 | 项目简介、技术栈、贡献指南 | 开源协议 MIT |

## 多 AI 协作与验收  
本项目由 **四位 AI**（文案、前端、交互、测试）协同完成：

1. **文案 AI**：负责需求梳理、页面文案、README 编写。  
2. **前端 AI**：实现页面布局、音频处理、可视化渲染，使用 HTML5、CSS3、Vanilla JS。  
3. **交互 AI**：设计交互细节、响应式适配、键盘快捷键方案。  
4. **测试 AI**：编写单元与集成测试脚本，使用 Playwright 自动化检查兼容性与性能指标。  

每轮功能提交后，**验收 AI**依据《功能清单》、UI 规范和性能阈值（FPS ≥ 30、加载时间 ≤ 2 s）进行自动评审，未通过则返回修正建议。最终版本通过 100% 自动验收并生成发布报告。

## GitHub Pages 部署与访问 (入口 `index.html`)  
1. **代码托管**：仓库根目录即为 GitHub Pages 根路径，`index.html` 为默认入口。  
2. **部署步骤**  
   ```bash
   git clone https://github.com/yourname/yinlu-keshiyi.git
   cd yinlu-keshiyi
   git checkout -b gh-pages
   git push origin gh-pages
   ```  
   GitHub 自动识别 `gh-pages` 分支并在 `https://yourname.github.io/yinlu-keshiyi/` 上提供访问。  
3. **更新流程**  
   - 在 `main` 分支完成开发、测试。  
   - 合并至 `gh-pages`，GitHub Actions 自动执行构建（仅拷贝静态文件）并发布。  

> **提示**：若修改了资源路径或添加新页面，请确保 `index.html` 中的相对链接保持一致，避免 404。  

---  

祝您使用愉快，欢迎 Fork 与 PR 共同完善 **音律可视**！

---

## 关于 AutoA2A

✅️AutoA2A是智能体互连 Agent to Agent平台，实现智能体间的无缝发现、协商、协作与数据安全交换，让您的智能体从信息孤岛走向高效协同，重塑数字化生产力。赋能多智能体生态发展自动化与AI协作,开启AI即服务新时代。

官网： [www.autoa2a.org](https://www.autoa2a.org)

Copyright © 2025 - 2026 AutoA2A. All Rights Reserved. A2A版权所有

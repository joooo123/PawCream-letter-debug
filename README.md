# PawCream Letter Debug

独立的品牌理念信纸调试站。该仓库只负责 GitHub Pages 预览，不修改 PawCream 正式站点或小红书工具端。

- 调试页面源码与所需素材从 [PawCream 的 debug-brand-letter-lab 分支](https://github.com/joooo123/PawCream/tree/debug-brand-letter-lab)同步。
- 推送到本仓库 main 分支后，GitHub Actions 会自动部署。
- 预览地址：https://joooo123.github.io/PawCream-letter-debug/xhs-letter-debug/

在调试网页中调整纸张宽度、高度、位置、文字区域和中英文大小，并可复制参数。

部署状态由 GitHub Actions 自动维护；若修改调试源，请重新运行 `Deploy Letter Debug Pages` 工作流。

调试页已更新：移动端信纸参数现与小红书分支默认值对齐，并放大模拟视口中的信封。推送此提交以触发 Pages 更新。

修正说明：移动端预览现在使用与小红书实际视口匹配的信封尺寸；桌面参数预览保持原尺寸。

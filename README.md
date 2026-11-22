# 以线，识形 · 量化线场

![预览](assets/preview.png)

**在线演示**：https://chenyiming-aaa.github.io/quantized-line-field/

把九枚 AI 品牌标识（DeepSeek、ChatGPT、Claude、Gemini、Grok、Qwen、智谱 GLM、Kimi、豆包）采样成 60×60 亮度网格，量化为四档线宽，再用竖线重绘——身份从光场中浮现。整站是一个自包含的 `index.html`，无依赖、无网络请求，双击即可运行。

机制：路径一次性采样为亮度表，按 0.12 / 0.42 / 0.89 三道阈值分成四档线宽，种子噪声缓慢漂移；指针拨线后弹簧回位，悬停显示蓝色检测框。支持漂移开关与减少动效模式，标识按真实包围盒归一化，视觉大小一致。

## 来源参考
- 风格与提示词契约：[StyleKit 量化线场](https://www.stylekit.top/styles/quantized-line-field/showcase)
- 版式参照：[brand-line-cards 实验](https://www.stylekit.top/experiments/brand-line-cards/index.html)
- 标识路径：[LobeHub Icons](https://github.com/lobehub/lobe-icons)（MIT），原始 SVG 见 `assets/logos/`

## 运行与部署
直接打开 `index.html`；或推送到 GitHub，在 Settings → Pages 选 main 分支根目录即可发布。

## 许可
代码 MIT。品牌名称与标识版权归各品牌所有，仅作非商业生成式视觉研究，不代表背书。
# 巧克力九重奏 · Chocolate Nonet Cake

巧克力九重奏 · Chocolate Nonet Cake 是一个纯前端的交互式烘焙教程网页，用 SVG 动画完整演示一款 6 寸十四层巧克力蛋糕的制作过程，27 个步骤配中英文食谱与实时原料扣减。

## 功能特性

- **结构化流程**：把布朗尼、戚风、慕斯、奶冻、黄油薄脆等复合结构拆解为 27 个制作步骤。
- **SVG 动画演示**：点击「下一步」逐步观看原料飞入、巧克力融化、蛋白打发、烘烤倒扣、逐层组装等矢量动画。
- **中英双语食谱**：每一步均配中英文食谱与操作提示，适合教学与展示。
- **实时原料扣减**：顶部原料栏显示各原料剩余用量，随步骤使用自动减少。
- **响应式布局**：适配桌面与移动端，成品页展示 8 张实拍照片。

## 技术栈 / 依赖

- 原生 HTML + CSS + JavaScript
- SVG 矢量图形与 CSS 动画
- 零第三方依赖、零构建步骤、无需服务器、无需联网

## 目录结构

```
Chocolate-Nonet-Cake-Recipe/
├── index.html        # 教程主页面（入口文件）
├── files/            # 成品展示配图
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   ├── 5.jpg
│   ├── 6.jpg
│   ├── 7.jpg
│   └── 8.jpg
├── README.md         # 项目说明
├── LICENSE           # 知识共享许可协议（详见下文）
└── .gitignore        # Git 忽略规则
```

## 快速开始

浏览器直接打开 `index.html` 即可，无需构建工具、无需服务器、无需联网：

```bash
git clone https://github.com/RockyproJiang/Chocolate-Nonet-Cake-Recipe.git
cd Chocolate-Nonet-Cake-Recipe
```

然后双击 `index.html`（或在浏览器中打开该文件）即可观看教程。

## 配置与安全说明

- 纯前端项目，无 API Key、无密钥、无后端，不上传任何数据，所有动画与食谱内容均在本地页面内。
- 配图位于 `files/` 目录，属于本地静态资源，无需联网加载。

## 许可证

本项目的许可类型不是 MIT。仓库内的 [LICENSE](LICENSE) 为 **知识共享「署名-非商业性使用 4.0 国际」（CC BY-NC 4.0）** 许可协议：允许复制、传播与改编，但须保留署名，且不得用于商业目的。具体条款详见 [LICENSE](LICENSE)。

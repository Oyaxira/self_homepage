# 个人导航页面

一个简洁优雅的个人导航页面，支持自定义背景图片和链接卡片，完全响应式设计适配各种设备。ai生成不含一点个人代码。

## 🌟 特性

- 💡 简洁现代的界面设计
- 🎨 支持自定义背景图片
- 📱 完全响应式设计，适配移动端
- 🔗 动态加载链接卡片
- 🎯 平滑的动画效果
- ⚡ 轻量级，加载迅速

## 🛠️ 技术栈

- HTML5
- CSS3
- JavaScript (原生)

## 📦 项目结构
```
project-root/
├── index.html # 主页面
├── style.css # 样式文件
├── config.json # 配置文件
├── favicon.png # 网站图标
└── assets/ # 资源文件夹
├── background.jpg # 背景图片
└── icons/ # 链接图标
```

## 🚀 快速开始

1. 克隆项目到本地：
2. 配置 `config.json`：
```json
{
  "title": "我的导航",
  "background": "assets/background.jpg",
  "links": [
      {
      "name": "GitHub",
      "url": "https://github.com",
      "icon": "assets/icons/github.png"
      },
  // 添加更多链接...
  ]
}
```
3. 部署到服务器或直接打开 `index.html`

## 📝 配置说明

### config.json 参数

- `title`: 页面标题
- `background`: 背景图片路径
- `links`: 链接卡片数组
  - `name`: 链接名称
  - `url`: 链接地址
  - `icon`: 图标路径

## 📱 响应式设计

- 桌面端：多列网格布局
- 平板端：适应性调整列数
- 移动端：单列显示
- 超小屏幕：优化显示效果

## 🎨 自定义样式

可以通过修改 `style.css` 文件来自定义样式：

- 修改卡片样式
- 调整动画效果
- 更改颜色主题
- 自定义字体

# 组件设计规范

## 卡片组件
- 背景：rgba(255, 255, 255, 0.8)
- 圆角：24px
- 阴影：0 4px 8px rgba(0,0,0,0.1)
- 过渡：transform 400ms cubic-bezier(0.4, 0, 0.2, 1)

## 按钮组件
- 填充色：#00ffff
- 文字色：#0c0c1d
- 圆角：20px
- 过渡：all 0.3s ease

## 装饰元素
- 数量：15个SVG元素
- 动画类型：浮动、旋转、缩放、波动
- 性能优化：will-change, transform 
# Shine Card Web

GPU 光泽效果的 Web 演示版本。

## 效果对比

| 特性 | Web (CSS) | Native (GPU) |
|------|-----------|--------------|
| 性能 | CSS 动画 60fps | GPU Shader 60fps |
| 光泽跟随 | 预定义动画 | 实时跟随触摸 |
| 彩虹全息 | CSS 渐变模拟 | 真实 Shader 计算 |
| 3D 倾斜 | ✅ 支持 | ✅ 支持 |

## 在线预览

<https://shine-card-web.vercel.app>

## 本地运行

```bash
npm run dev
```

## 部署

```bash
npm i -g vercel
vercel
```

## 相关项目

- [shine-card](https://github.com/muvich3n/shine-card) - React Native 原生版本（使用 react-native-shine）

# 前端性能优化学习路径

## 一、性能指标
### 1. 核心指标
- FCP (First Contentful Paint)
- LCP (Largest Contentful Paint)
- FID (First Input Delay)
- CLS (Cumulative Layout Shift)
- TTI (Time to Interactive)
- TBT (Total Blocking Time)

### 2. 性能监控
- Performance API
- Web Vitals
- 性能埋点
- 错误监控
- 用户体验数据

## 二、加载优化
### 1. 资源加载
- 资源压缩
- 图片优化
  - WebP
  - 响应式图片
  - 懒加载
  - 预加载
- 字体优化
- 视频优化

### 2. 构建优化
- 代码分割
- Tree Shaking
- 路由懒加载
- 预渲染
- 服务端渲染

### 3. 缓存策略
- HTTP 缓存
- Service Worker
- 离线存储
- CDN 优化
- 浏览器缓存

## 三、运行时优化
### 1. JavaScript 优化
- 代码执行优化
- 内存管理
- 垃圾回收
- 事件处理
- 防抖节流

### 2. 渲染优化
- 重排重绘
- 合成层优化
- 动画性能
- 虚拟列表
- DOM 操作优化

### 3. 框架优化
- React 优化
  - useMemo
  - useCallback
  - React.memo
  - 虚拟列表
- Vue 优化
  - 响应式优化
  - 编译优化
  - 静态提升
  - keep-alive

## 四、网络优化
### 1. 请求优化
- HTTP/2
- HTTP/3
- DNS 预解析
- 预连接
- 资源预加载

### 2. API 优化
- 接口合并
- 数据缓存
- 请求排队
- 错误重试
- 并发控制

## 五、体验优化
### 1. 加载体验
- 骨架屏
- 预加载
- 进度反馈
- 加载动画
- 渐进式加载

### 2. 交互体验
- 即时反馈
- 动画过渡
- 手势操作
- 页面流畅度
- 离线体验

## 六、性能测试
### 1. 测试工具
- Lighthouse
- Chrome DevTools
- WebPageTest
- Performance API
- 性能监控平台

### 2. 测试方法
- 性能基准
- A/B 测试
- 压力测试
- 实验室数据
- 实际用户监控(RUM)

## 七、最佳实践
### 1. 开发规范
- 代码优化
- 资源管理
- 构建配置
- 发布流程
- 监控告警

### 2. 性能预算
- 指标设定
- 监控方案
- 告警策略
- 优化流程
- 效果评估

## 八、推荐资源
### 1. 工具文档
- [Web Vitals](https://web.dev/vitals/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

### 2. 学习资源
- [Web Performance](https://web.dev/learn/#performance)
- [性能优化指南](https://developers.google.com/web/fundamentals/performance/get-started)

## 九、实战项目
- 性能监控平台
- 性能优化工具
- 自动化测试
- 优化案例实践 
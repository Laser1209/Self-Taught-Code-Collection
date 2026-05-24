# Self-Taught-Code-Collection
# 前端自学·完整学习轨迹总结报告

> 审查范围：`Part One_HTML & CSS` + `Part Two_JavaScript` + `Self‑Taught Code Collection`
> 审查日期：2026-05-25
> 作者：李宜泽 (Laser / Etta)

---

### 工程化体系

每个项目统一配置 **Webpack 5 + Babel 7 + ESLint 8 + Jest 29**，52个测试用例全部通过。

### 门户网站：个人作品集

极简黑白风格，集成了Perlin噪声波浪、包豪斯开场动画、Anime.js动画编排、砖块滑动门过渡等设计元素。

---

## 技术领域及知识点汇总

### HTML
- 语义化标签（header/main/nav/footer/section/article）
- 表单元素全系列（input/select/textarea/button/label）
- 多媒体标签（video/audio）
- 锚点定位、SEO基础

### CSS
- **布局体系**：浮动(float)、定位(position 5种)、Flexbox(弹性盒子)、多列(column)
- **盒子模型**：标准盒模型、怪异盒模型(border-box)、margin塌陷
- **响应式**：媒体查询(@media)、vw/vh视口单位、rem适配
- **动画系统**：过渡(transition)、2D变换、3D变换(透视+立方体)、关键帧动画(@keyframes)、逐帧动画(steps)
- **CSS3选择器**：属性选择器、结构伪类(:nth-child/:first-child)、目标伪类(:target)、否定伪类(:not)
- **视觉增强**：阴影(box-shadow/text-shadow)、渐变、自定义字体(@font-face)、矢量图标(iconfont)、CSS Sprite、混合模式(mix-blend-mode)

### JavaScript
- **基础语法**：变量(var/let/const)、数据类型、类型转换、运算符、条件语句、循环
- **函数**：声明/表达式/箭头函数、参数/返回值、递归、闭包、柯里化、预解析(hoisting)
- **内置对象**：Math/Date/String/Array/Object方法全系
- **DOM**：节点查询/创建/删除/克隆、样式操作、属性操作、类名操作
- **事件系统**：事件绑定/解绑、事件对象、事件传播(捕获/冒泡)、事件委托、键盘/表单/触摸事件
- **BOM**：window对象、浏览器尺寸、滚动控制、location/history、弹出层
- **ES6+**：箭头函数、解构赋值、展开运算符、模板字符串、Class类
- **高级概念**：this绑定规则、call/apply/bind、闭包、函数柯里化、防抖(debounce)、正则表达式、发布订阅模式
- **Canvas API**：2D渲染、游戏循环(requestAnimationFrame)、碰撞检测(AABB)、粒子系统
- **异步基础**：setTimeout/setInterval、clearTimeout

### 工程化
- **Webpack 5**：模块打包、开发服务器、生产构建
- **Babel 7**：ES6+语法转译
- **ESLint 8**：代码规范检查
- **Jest 29**：单元测试（mock浏览器API策略）
- **npm**：包管理、脚本配置

### Node.js
- **HTTP Server**：纯`http`模块构建静态文件服务器
- **MIME类型处理**：自定义映射表
- **部署方案**：ngrok内网穿透/frp自建方案

### 设计能力
- 极简黑白风格设计体系（CSS变量统一色板）
- CSS动画编排（Anime.js timeline）
- Web Component 自定义元素
- Perlin噪声算法实现
- 响应式设计（桌面端/移动端双版本）
- 自定义鼠标指针交互

---

## 技能发展的阶段性特点

### 🔰 第一阶段：HTML/CSS 静态页面 (Part One Day01-13)
- 掌握HTML5语义化标签和表单全系
- CSS盒子模型+定位系统成为肌肉记忆
- 能独立复刻商业页面（小米官网）
- **弱点**：无JavaScript加持，页面缺乏交互

### 🟡 第二阶段：JavaScript 基础编程 (Part Two Day01-13)
- 从变量/循环到DOM/事件
- 完成贪吃蛇、放大镜等交互应用
- 开始使用独立JS文件组织代码
- **突破**：事件委托、BOM、瀑布流标志BOM/DOM体系完整建立

### 🟠 第三阶段：ES6+ 现代化 + 高级概念 (Part Two Day14-22)
- `let/const`替代`var`，箭头函数替换普通函数
- 闭包、柯里化、防抖、正则、发布订阅模式
- 运动函数(`move.js`)封装——动画引擎雏形
- **突破**：this绑定规则透彻理解，从面向过程到面向对象

### 🔴 第四阶段：工程化 + 综合项目 (Self-Taught Collection)
- 引入Webpack 5 + Babel 7 + ESLint 8 + Jest 29 完整工具链
- 7个项目全部有单元测试（52/52通过）
- Canvas游戏开发全能力（贪吃蛇→魂斗罗）
- 玩家物理、粒子系统、碰撞检测等游戏引擎概念
- 设计系统统一（CSS变量、极简黑白风格）
- **突破**：观察者模式、测试驱动开发、完整的部署方案

---

## 能力矩阵总结

| 能力维度 | 掌握程度 | 说明 |
|----------|----------|------|
| HTML语义化 | ⭐⭐⭐⭐⭐ | 标签全系熟练，表单/多媒体均掌握 |
| CSS布局 | ⭐⭐⭐⭐⭐ | Flexbox/Position/Grid(基础)/Float全掌握 |
| CSS动画 | ⭐⭐⭐⭐⭐ | 过渡→2D→3D→关键帧→逐帧，技术链完整 |
| 响应式设计 | ⭐⭐⭐⭐ | 媒体查询+vw/vh+rem适配，移动端页面实战 |
| JavaScript语法 | ⭐⭐⭐⭐⭐ | ES6+全面掌握，从var到const的进化为证 |
| DOM/BOM | ⭐⭐⭐⭐⭐ | 事件系统、节点操作、浏览器API完整掌握 |
| Canvas游戏开发 | ⭐⭐⭐⭐ | 7款游戏，物理引擎/碰撞检测/粒子系统 |
| 正则表达式 | ⭐⭐⭐⭐ | 手机号/邮箱验证，贪婪/懒惰模式 |
| 高阶JS | ⭐⭐⭐⭐ | 闭包/柯里化/防抖/发布订阅/this全掌握 |
| 前端工程化 | ⭐⭐⭐⭐ | Webpack+Babel+ESLint+Jest完整工具链 |
| 单元测试 | ⭐⭐⭐⭐ | 52个Jest测试用例，mock策略成熟 |
| Node.js基础 | ⭐⭐⭐ | HTTP服务器、文件系统、MIME处理 |
| 视觉设计 | ⭐⭐⭐⭐ | 极简设计体系、CSS动画编排、品牌统一 |

---

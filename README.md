
# Three.js 学习笔记

### 01 Basics

- 03 - Basic scene
  - 下载并引入 three.js 文件
  - 学习 `场景` `物体` `相机` `渲染器` 等概念和使用
  - 创建一个红色立方体并显示在屏幕上

- 05 - Transform objects
  - 学习 `position` `scale` `rotation` 相关操作
  - 学习 `AxesHelper` 辅助坐标系的使用
  - 让相机看向任意三维坐标或物体中心
  - 学习 `Group` 组的基本概念和使用

- 06 - Animations
  - 使用 `requestAnimationFrame` 实现动画
  - 让物体在不同帧率下都保持同样的运动轨迹
  - 使用 `THREE.Clock` 实现动画
  - 使用 `gsap` 来实现动画

- 07 - Cameras
  - 学习 `PerspectiveCamera` 透视相机的概念和 `z-fighting` 现象
  - 学习 `OrthographicCamera` 正交相机的概念和使用
  - 通过鼠标移动来改变相机的位置
  - 学习 `OrbitControls` 轨道控制器的概念及使用

- 08 - Fullscreen and resizing
  - 设置 canvas 画布的尺寸撑满页面
  - 监听 onresize 触发时重新设置画布尺寸
  - 了解屏幕像素比, 设置 dpr 使画布渲染更加清晰
  - 监听鼠标双击事件触发时进入全屏模式

- 09 - Geometries
  - 学习立方体是如何通过顶点组成若干三角形绘制的
  - ~~学习 `Geometry` 自定义顶点信息创建几何图形~~ (已废弃)
  - 学习 `BufferGeometry` 自定义顶点信息创建几何图形

- 10 - Debug UI
  - 学习使用 `dat.gui` 调试 `坐标` `颜色` `旋转` 等参数

- 11 - Textures
  - 学习使用 img 标签加载纹理, 以及 `TextureLoader` 纹理加载器
  - 学习纹理的 `重复平铺` `镜像重复` `偏移量` `旋转` `过滤器`

- 12 - Materials
  - 学习不同材质的特性以及对应属性
  - 学习使用各种贴图实现不同的效果, 并调试显示程度
  - 学习使用 `立方体纹理加载器` 设置环境贴图

- 13 - 3D Text
  - 学习使用 `FontLoader` 加载并渲染 3D 文字
  - 使用 `Matcap` 贴图作为字体的纹理
  - 渲染 300 个同样纹理的甜甜圈作为点缀

### 02 Classic techniques

- 15 - Lights
  - 学习各种灯光的效果和使用场景, 以及各种灯光的辅助工具

- 16 - Shadows
  - 学习如何产生阴影, 并调试阴影的参数和投射范围
  - 使用 `CameraHelper` 观察三种光源的投射方位
  - 使用纹理贴图模拟阴影效果来节省内存


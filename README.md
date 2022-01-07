
# Three.js 学习笔记

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

color

ALPHA
Grayscale image
White visible
Black not visible
阿尔法
灰度图像
白色可见
黑色不可见

HEIGHT ( OR DISPLACEMENT )
Grayscale image
Move the vertices to create some relief
Need enough subdivision
高度（或位移）
灰度图像
移动顶点以创建一些浮雕
需要足够的细分吗

NORMAL
Add details
Doesn't need subdivision
The vertices won't move
Lure the light about the face orientation
Better performances than adding a height texture with a lot of subdivision
典型的
添加详细信息
不需要细分
顶点不会移动
将灯光吸引到脸部方向
与添加高度纹理和大量细分相比，性能更佳

AMBIENT OCCLUSION
Grayscale imageAdd fake shadows in crevices
Not physically accurateHelps to create contrast and see details
环境遮挡
灰度图像在裂缝中添加假阴影
物理上不准确有助于创建对比度和查看细节

METALNESS
Grayscale image
White is metallic
Black is non-metallic
Mostly for reflection
金属性
灰度图像
白色是金属色的
黑色是非金属的
主要是为了反思

ROUGHNESS
Grayscale image
In duo with the metalness
White is rough
Black is smooth
Mostly for light dissipation
粗糙度
灰度图像
和金属性二重奏
白色是粗糙的
黑色是光滑的
主要是为了消光


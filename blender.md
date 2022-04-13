## Blender

F12 渲染预览  
G grab 拖动  
G + X(Y,Z) 沿着x(y,z)拖动  
R rotation 旋转  
S scale 缩放  
Shift + 空格  预览快捷键  
触摸板2个手指视角转换，command + 2个手指，视角缩放  
鼠标中键旋转视角，或者Alt(Option) + 鼠标左键，或者右上角XYZ坐标  
Shift + 鼠标中键 拖动视角，或者Shift + Alt(Option) + 鼠标左键，或者右侧手型图标
~ 按住可以选择转换视角  
Shift + D 复制Object  
X 删除  
Shift + C Cursor回归原点  
Shift + S 物体回归原点选择  
Shift + A 创建新物体  
F9 物体属性设置，在刚创建物体时会显示，后续消失，F9重新唤出  
N 唤出position, size等物体transform属性  
Control(Ctrl) + A 应用各种变换，例如将scale重新设置为（1，1，1）  
鼠标右键（触摸板是2个手指）shader flat/smooth 切换

Modifier + Sub Surface 细分表面  
Tab键 Edit/Object Mode切换 Ctrl + Tab 进入更多模式

按O进入顶点拖拽：
先按住G不放，双指缩放，看左上角Proportion Size, 出现灰色圆圈后，松开G，按住control+双指拖动
S同上  

Select菜单中有个随机选取顶点的功能  

Alt + Z 切换透明网格，用于选取背面网格  

P 选择，将网格点连接起来  

属性里修改数值时，可以按住Shift 或 Control/Ctrl 来调整微调数值增加值  

H，Alt(Option + H) 切换物体显示  

在Edit Mode下，按住Alt(Option) +鼠标左键选择边，环选（Edge Loop）

选中相机状态下，按Ctrl + Alt + NumPad将以当前视角screenshut

Alt + G, 任何选中的对象都会移到视口中心

Ctrl + Tab 呼出编辑模式 Weight Editor可以用来修改Weight, 右键修改Weight来重涂颜色， F是笔刷大小，Shift + F是笔刷力度, Ctrl + F控制weight值  

Ctrl + R 选择环切（Loop Cut）, 用鼠标滚轮可以增进环切数目  
Ctrl + A 应用（Apply）物体的各种变化(Transform)（3D打印时这个要注意）
Shift + 鼠标左键选中Object，然后再Shift + 鼠标左键选择一个Object, Ctrl + L 就可以选择 Link Material 到最后一次选择的Object (类似copy material from the last selected object)

Shift + 左键先选择其中一个Object，然后再按Shift + 左键选择另一个。这时按住Ctrl + P，使前者Object的parent指向为后者（即后者是前者的的Parent）

### Shader Nodes  
- 点击菜单Shading可以呼出Node节点，Node节点从左到右执行，Node之间连线可以用鼠标垂直滑动切开表示断开连接（类似切水果）  
- Add-ons里开启Node Wrangler可以看每个Node节点对物体shader的效果（Ctrl + Shift + 鼠标左键来选择Node节点）  

### Texture Editor  
- 对多个输入框同时处理，左键点击其中一个输入框不放，然后拖动到其他输入框，放开左键，那么就会同时选中多个输入框进行同时输入数值  
-  进入Texture Paint后，选中UV Editor，并开启同步选择器（UV Sync Selector）在选择模型表面同时也会选中UV图片  
-  在Textur Paint中， F是笔刷大小，Shift + F是笔刷力度  
-  X键可以切换最近选择的2中颜色  

### Geometry Nodes  
- Instance on Points的instance可以从右上角的Object直接拖过来  
- 悬浮于输入框时，按I可以插入关键帧  
- Shift + 右方向键可以设置末尾关键帧  
- 可以在任何地方加入关键帧比如材质颜色  
- 在输入框里输入#frame表示值随关键帧变化  
- Ctrl + J 插入Layout/Frame，用于对Node节点做注释  
- 按N可以调出Node节点框（在原本右侧小箭头处）  

### Camera  
Focal Length 值越大，画面深度越小，物体间的前后关系不容易识别。  
Clip Start 靠近相机裁剪位置，值越小，裁剪开始位置离镜头越近。  
I 插入关键帧
左下角的 Playback 里的Frame dropping可以让动画预览时按正常速度播放，复杂模型为了不掉帧，会降低播放速度（比实际播放时间长）

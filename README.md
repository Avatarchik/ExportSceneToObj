
# ExportSceneToObj
`ExportSceneToObj`用于`Unity`中导出场景（包括`GameObject`和`Terrian`）到`.obj`文件的`Editor`脚本。

### 功能：
* 支持导出物件和地形
* 支持自定义裁剪区域
* 提供自动裁剪功能

### 用法：
* 放到`Unity`的`Editor`目录下
* 如果要自定义裁剪区域的话，场景中增加裁剪区域（左下角和右上角）
* 修改代码中`CUT_LB_OBJ_PATH`和`CUT_RT_OBJ_PATH`
* 在`Unity`的菜单栏上有`ExportScene`菜单即可

### 其他：
目前判断物件是否在裁剪区域只是判断物件的坐标是否在区域内，还没有实现物件边界裁剪。

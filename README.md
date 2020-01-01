# JAVHelper GUI V0.0.2

本工具为使用Electron打包的JAVHELPER前端应用. 用户可以直接双击应用程序打开, Electron将在后台自动
运行 python 后端. 版本号将和后端手动版本保持一致.

后端手动访问版本:[JAVHELPER](https://github.com/ddd354/JAVHELPER)

## Installation

下载来自本repository的release. 提供MacOS和Windows版本. 本程序使用5000端口, 必须确保此端口目前可以使用.

## Usage

下载后解压缩, 双击run文件运行程序.

工作流程和后端手动版本相同:
* 选择 Settings 选项卡, 填入 / 修改需要的选项和参数.
* 选择 Main Tool 选项卡, 填入需要整理的路径, 选择 preview 选项并按下 Execute 按钮.
* 浏览表单下方的表格, 确定路径和文件正确(当前并不会处理子文件夹内部的文件).
* 如果需要进行文件重命名, 进行以下步骤, 否则可以跳过重命名部分.
* 如有需要, 选择 preview_rename 选项并按下 Execute 按钮.
* 浏览表单下方的表格, 确定所有文件都被正确地重命名.
* 选择 preview_rename 选项并按下 Execute 按钮, 观察上方的运行记录, 确保重命名正确.
* 选择 preview 选项并按下 Execute 按钮来刷新下方的表格, 确定路径和文件正确.
* 选择 parse_jav 选项并按下 Execute 按钮, 后台将会爬取 javLibrary 和 arzon 的视频文件信息.
* 观察上方的运行记录, 确保文件被正确地处理.


## License
[MIT](https://choosealicense.com/licenses/mit/)

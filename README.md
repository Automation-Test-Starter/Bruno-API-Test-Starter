
# bruno-cli-demo

**Chinese** | [English](/README_EN.md)

## 为什么选择 bruno

官方说明：https://github.com/usebruno/bruno/discussions/269

与 postman 的对比：https://www.usebruno.com/compare/bruno-vs-postman

开源,MIT License

客户端全平台支持 (Mac/linux/Windows)

离线客户端，无云同步功能计划

支持 Postman/insomina 脚本导入（只能导入 API 请求脚本，无法导入测试脚本/环境变量）

社区相对活跃，[产品开发路线图](https://github.com/usebruno/bruno/discussions/384)清晰


## 安装 bruno

Download link: <https://www.usebruno.com/downloads>

Mac 电脑推荐 brew 命令下载

​    `brew install Bruno`

## 客户端使用入门

### 默认主界面

![homepage](/readme_pictures/homepage.png)

### API collection 操作

#### 创建 API collection

- 首页点击‘Create Collection’链接, 打开创建 API collection 的弹窗

- 弹窗上依次输入

  Name: 输入API collection 的名字

  

  Location：输入想要保存API collection文件的文件夹路径(建议选择此项目所在路径)

  

  Folder Name：可输入API collection 的名字（会在刚才选择的路径下创建一个对应名字的文件夹）

  

- 点击Create 按钮即可完成API collection的创建，并展示在界面上(左侧collection列表会展示新建的API collection信息)

![create-collection](/readme_pictures/create-collection.png)

#### 打开 API collection

- 首页点击‘Open Collection’链接, 打开选择已有的bruno格式的API collection文件夹
- 点击open即可完成选择，并展示在界面上(左侧collection列表会展示选择的API collection信息)

#### 导入 API collection

- 首页点击‘Import Collection’链接, 打开导入 API collection 的弹窗(支持Bruno/Postman/Insomnia 的导入)
- 弹窗上选择对应格式的的链接，再选在已存在的对应格式的文件路径
- 点击open即可完成选择，并展示在界面上(左侧collection列表会展示选择的API collection信息)

![import-collection](/readme_pictures/import-collection.png)

#### 本地运行API collection

- 在主界面左侧collection列表选择想要运行的API collection，右键打开菜单
- 在菜单上选择Run，右侧界面会打开Runner tab，会展示所选择API collection里面requests的一些信息
- 点击Run Collection按钮即可本地运行(运行完界面上会展示允许结果)

#### 导出API collection

- 在主界面左侧collection列表选择想要运行的API collection，右键打开菜单
- 在菜单上选择Export，再选择想要导出文件的路径即可完成导出(导出文件也是为 json格式)

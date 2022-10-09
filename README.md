# WPFAdmin
WPF实现管理系统
## 一、系统设计大纲

```c#
WPFAdmin
├── WPFAdmin.Client  //客户端（前端）
│   ├── WPFAdmin.Client.Common  //公共方法层
│   ├── WPFAdmin.Client.Models  //模型层
│   ├── WPFAdmin.Client.Reference  //引用、公共资源层
│   ├── WPFAdmin.Client.Services  //服务层
│   ├── WPFAdmin.Client.Themes  //主题资源层，各种控件样式、图标
│   ├── WPFAdmin.Client.UIControls  //常用的用户控件层
│   ├── WPFAdmin.Client.ViewModels  //视图模型逻辑层
│   ├── WPFAdmin.Client.Views  //视图层，展示的页面    
│   └── WPFAdmin.Client.WpfConvert  ///WPF中用到的类型转换层
└── WPFAdmin.Service  //服务端（后端）
    ├── WPFAdmin.Service.Application  //业务应用层
    ├── WPFAdmin.Service.Core  //核心层（实体，仓储，其他核心代码）
    ├── WPFAdmin.Service.Database.Migrations  //EFCore 架构迁移文件层
    ├── WPFAdmin.Service.EntityFramework.Core  //EF Core 配置层
    ├── WPFAdmin.Service.Web.Core  //Web 核心层
    └── WPFAdmin.Service.Web.Entry  //入口层/启动层
```

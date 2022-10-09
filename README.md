# Admin.WPF
WPF实现管理系统
## 一、系统设计大纲

```c#
Admin.WPF
├── Admin.WPF.Client  //客户端（前端）
│   ├── Admin.WPF.Client.Common  //公共方法层
│   ├── Admin.WPF.Client.Models  //模型层
│   ├── Admin.WPF.Client.Reference  //引用、公共资源层
│   ├── Admin.WPF.Client.Services  //服务层
│   ├── Admin.WPF.Client.Themes  //主题资源层，各种控件样式、图标
│   ├── Admin.WPF.Client.UIControls  //常用的用户控件层
│   ├── Admin.WPF.Client.ViewModels  //视图模型逻辑层
│   ├── Admin.WPF.Client.Views  //视图层，展示的页面    
│   └── Admin.WPF.Client.WpfConvert  ///WPF中用到的类型转换层
└── Admin.WPF.Service  //服务端（后端）
    ├── Admin.WPF.Service.Application  //业务应用层
    ├── Admin.WPF.Service.Core  //核心层（实体，仓储，其他核心代码）
    ├── Admin.WPF.Service.Database.Migrations  //EFCore 架构迁移文件层
    ├── Admin.WPF.Service.EntityFramework.Core  //EF Core 配置层
    ├── Admin.WPF.Service.Web.Core  //Web 核心层
    └── Admin.WPF.Service.Web.Entry  //入口层/启动层
```

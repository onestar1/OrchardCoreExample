# OrchardCoreExample

OrchardCore应用示例 更新orchardcore版本引用为1.8.2

## 示例说明

| 项目 | 说明 |  功能说明
|--------|--------|----|
|[OrchardCoreExample.Application.WebHost](src/Applications/OrchardCoreExample.Application.WebHost)						|Demo宿主|  主项目,设置了降低密码难度
|[OrchardCoreExample.Settings.Module](src/Modules/OrchardCoreExample.Settings.Module)		|示例设置模块| 包含权限,导航,设置功能演示
|[OrchardCoreExample.WebApi.Module](src/Modules/OrchardCoreExample.WebApi.Module)		|webapi示例模块|包含权限,webapi配合openid授权验证,Swagger实现
|[OrchardCoreExample.Workflows.Module](src/Modules/OrchardCoreExample.Workflows.Module)		|工作流示例模块|包含工作流事件,任务,通过api触发
|[OrchardCoreExample.DataTable.Module](src/Modules/OrchardCoreExample.DataTable.Module)		|创建数据表|包含自定义表的创建,以及数据管理
|[OrchardCoreExample.WeCharMiniProgram.Module](src/Modules/OrchardCoreExample.WeCharMiniProgram.Module)		|微信小程序后端实现|包含用户信息授权,解密手机号等,加入了OpenId权限
|[OrchardCore.Swagger.Abstractions](src/Modules/OrchardCore.Swagger.Abstractions)		|Swagger.Abstractions|Swagger.Abstractions
|[OrchardCore.Swagger](src/Modules/OrchardCore.Swagger)		|Swagger|Swagger
|[OrchardCoreExample.AliYunSecurityTokenService.Module](src/Modules/OrchardCoreExample.AliYunSecurityTokenService.Module)		|示例阿里云STS授权模块|示例阿里云STS授权
|[AliYunSecurityTokenServiceExample](Examples/AliYunSecurityTokenServiceExample)		|阿里云STS授权模块客户端示例|示例使用OrchardCodeOpenId授权,获取阿里云STS授权

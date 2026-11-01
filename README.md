# pz-launcher

本仓库是 Project Zomboid B42.22 整合包启动器的**成品发布与更新源**，不是源码仓库。

## 下载

请只从本仓库的 [Releases](https://github.com/grshlogan/pz-launcher/releases) 下载。

| 版本 | 文件 | 大小 | sha256 |
| --- | --- | --- | --- |
| v0.2.0 | `pz-launcher.exe` | 19,042,816 B | `ab11b30d7a409fbf08018566f2cb57218449607bc7a551ebea14f8548c3425e1` |

支持 Windows 10/11 x64，游戏版本 B42.22。

## 这个仓库是什么

- 只存放编译后的启动器 Release 资产；
- 不存放源码、构建脚本或开发文档；
- 启动器更新以本仓库的 Releases 为权威来源；
- 源码将在独立平台仓库发布后另行提供链接，本仓库不会携带旧源码历史。

## 使用

1. 从 Releases 下载 `pz-launcher.exe`；
2. 校验文件大小和 sha256；
3. 运行启动器，按界面选择游戏目录和载荷；
4. 更新时回到本仓库 Releases 获取新版本。

校验示例：

```powershell
Get-FileHash .\pz-launcher.exe -Algorithm SHA256
```

## 安全与责任

- 只从本仓库 Release 下载；不要使用来源不明的启动器或 DLL。
- 平台/第三方使用者自行负责其 payload、DLL 校验和签名密钥配置。
- 本仓库不提供我方整合包的真实资源路径、服务器地址、私钥或密钥材料。
- 本仓库不提供游戏本体的下载；请自行准备合法游戏副本。

## 版本

- `v0.2.0`：首个公开二进制发布，保留既有 Release 资产与校验和。

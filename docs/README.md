# 简介

[目录](_sidebar.md)

> Linux 操作系统 蓝牙 键盘 鼠标 耳机 适配清单

如何优雅的阅读本文档？

只需要运行shell脚本，然后打开浏览器访问 `http://localhost:3000` 即可

- Linux  
`bash docs/run.sh`

- Else  
    - python 3  
        `cd docs && python -m http.server 3000`
    - python 2  
        `cd docs && python -m SimpleHTTPServer 3000`
    - docsify  
        `docsify serve docs`

# 格式

## 清单格式

```bash
| 设备名称 | 操作系统 | 适配器 | 测试人 |
|--|--|--|--|
| 小米便携鼠标（MiMouse） | Linux arch 5.11.6 | RTL8822CE |[kearney](mailto:191615342@qq.com)|
| 罗技（Logitech）MX Anywhere 2S | Linux arch 5.11.6 | AX200 |[BackMountainDevil](https://github.com/BackMountainDevil)|
```

测试人请添加自己的联系方式超链接，一般为github用户首页（上面有你的邮箱），也可以直接写邮箱，除了填写清单，还需要填写测试信息。

实际预览效果

| 设备名称 | 操作系统 | 适配器 | 测试人 |
|--|--|--|--|
| 小米便携鼠标（MiMouse） | Linux arch 5.11.6 | RTL8822CE |[kearney](mailto:191615342@qq.com)|
| 罗技（Logitech）MX Anywhere 2S | Linux arch 5.11.6 | AX200 |[BackMountainDevil](https://github.com/BackMountainDevil)|


## 测试信息格式

```bash
### 小米便携鼠标
- 时间 : 2021.5.20
- 设备名称 : 小米便携鼠标 - MiMouse - XMSB02MW
- 操作系统 : Linux arch 5.11.6-arch1-1 #1 SMP PREEMPT Thu, 11 Mar 2021 13:48:23 +0000 x86_64 GNU/Linux
- 适配器 : RTL8822CE 802.11ac
- 状态 : 全部功能测试通过
- 相关信息 : 其他你认为有价值的信息
```

实际预览效果

### 小米便携鼠标
- 时间 : 2021.5.20
- 设备名称 : 小米便携鼠标 - MiMouse - XMSB02MW
- 操作系统 : Linux arch 5.11.6-arch1-1 #1 SMP PREEMPT Thu, 11 Mar 2021 13:48:23 +0000 x86_64 GNU/Linux
- 适配器 : RTL8822CE 802.11ac
- 状态 : 全部功能测试通过
- 相关信息 : 其他你认为有价值的信息

由 [docsify](https://github.com/docsifyjs/docsify) 提供文档支持
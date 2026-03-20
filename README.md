# Omvian Hub Releases

本仓库用于存放 Omvian Hub 程序的发布文件和依赖库配置。

## 目录结构

```
omvian-hub-releases/
├── dependencies/
│   └── registry.json    # 依赖库注册表
└── README.md
```

## 依赖库注册表

`dependencies/registry.json` 文件定义了 Omvian Hub 支持的依赖库列表。

### 当前支持的依赖库

| 依赖库 | 版本 | 许可证 | 官方下载渠道 |
|--------|------|--------|-------------|
| FFmpeg | 8.0.1 | LGPL-3.0-or-later | https://www.gyan.dev/ffmpeg/builds/ |

### 注册表格式

```json
{
  "version": "2.0.0",
  "updatedAt": "2026-03-20T00:00:00Z",
  "libraries": [
    {
      "id": "ffmpeg",
      "name": "FFmpeg",
      "version": "8.0.1",
      "download": {
        "official": {
          "baseUrl": "https://www.gyan.dev/ffmpeg/builds",
          "filePattern": "ffmpeg-{version}-full_build-shared.7z"
        }
      },
      "platforms": { ... },
      "license": { ... }
    }
  ]
}
```

## 版本说明

- **备案版本**：程序只支持 registry.json 中备案的固定版本
- **官方渠道**：所有依赖库从官方渠道下载，确保稳定性和许可证合规

## 许可证声明

本仓库中的依赖库各自遵循其原始许可证：

- FFmpeg: [LGPL-3.0-or-later](https://ffmpeg.org/legal.html)

---

*Omvian Hub - 现代化的桌面应用工具平台*

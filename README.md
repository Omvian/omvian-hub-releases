# Omvian Hub Releases

本仓库用于存储 Omvian Hub 的安装包和公共依赖库。

## 目录结构

```
omvian-hub-releases/
├── releases/                     # 安装包发布目录
│   └── v1.0.0/
│       └── OmvianHub-Setup-1.0.0.exe
├── dependencies/                 # 依赖库目录
│   ├── registry.json            # 依赖库清单（核心文件）
│   └── ffmpeg/
│       └── 6.0.0/
│           └── ffmpeg-6.0.0-win-x64.zip
└── README.md
```

## 依赖库说明

### FFmpeg

- **版本**: 6.0.0
- **许可证**: LGPL-2.1-or-later
- **主页**: https://ffmpeg.org
- **描述**: 多媒体处理框架，支持视频/音频转码、剪辑、合并等操作

## 许可证声明

本仓库中的依赖库各自遵循其原始许可证：

- FFmpeg: [LGPL-2.1-or-later](https://ffmpeg.org/legal.html)

# _resource 目录说明

此目录用于存放博客文章所引用的静态资源文件，包括：

- **图片**（`.png`、`.jpg`、`.gif`、`.svg` 等）
- **音频**（`.mp3`、`.ogg` 等）
- **视频**（`.mp4`、`.webm` 等）

## 引用方式

在 `_blog/` 目录的 Markdown 文件中，通过绝对路径引用本目录中的资源：

```markdown
<!-- 图片 -->
![描述文字](/resource/images/example.png)

<!-- 音频 -->
<audio controls src="/resource/audio/example.mp3"></audio>

<!-- 视频 -->
<video controls src="/resource/video/example.mp4"></video>
```

## 建议的子目录结构

```
_resource/
├── images/   # 图片资源
├── audio/    # 音频资源
└── video/    # 视频资源
```

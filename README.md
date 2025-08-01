# 片假字日语词典

这是一个包含中文和日语片假字读音意思对比的词典，内容涵盖日常用语句式、典故、音律、诗歌、风景名胜、文化古迹、音乐与动漫等丰富信息，并制作成EPUB电子书格式。

## 项目结构

请查看 [project_structure.md](project_structure.md) 了解完整的项目目录结构。

## 内容章节

1. 片假字基础知识
2. 片假字读音与意思对比
3. 日常用语句式
4. 典故与历史
5. 文化古迹
6. 风景名胜
7. 音律与诗歌
8. 音乐与动漫中的片假字
9. 片假字的未来发展与学习建议

## 构建EPUB电子书
>需先安装pandoc和wkhtmltopdf这两个工具

### 使用Node.js脚本构建（推荐）

```bash
npm run build
```

### 使用Node.js脚本生成PDF

```bash
npm run build:pdf
```

如果 `wkhtmltopdf` 安装在不同的位置，可以通过设置环境变量 `WKHTMLTOPDF_PATH` 来指定其路径：

```bash
# Windows (Command Prompt)
set WKHTMLTOPDF_PATH="C:\Program Files\wkhtmltopdf\bin\wkhtmltopdf.exe"
npm run build:pdf

# Windows (PowerShell)
$env:WKHTMLTOPDF_PATH="C:\Program Files\wkhtmltopdf\bin\wkhtmltopdf.exe"
npm run build:pdf

# macOS/Linux
export WKHTMLTOPDF_PATH=/usr/local/bin/wkhtmltopdf
npm run build:pdf
```

## 许可证

MIT

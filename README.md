# YangHang's Toolbox

实用在线开发工具集，纯前端实现，无需后端服务，打开即用。

**在线地址**: [https://yanghang0210.github.io](https://yanghang0210.github.io)

## 工具列表

| 工具 | 说明 |
|------|------|
| [JSON 工具](https://yanghang0210.github.io/tools/json.html) | 格式化、压缩、校验、树形视图，支持语法高亮与错误定位 |
| [JSON Diff](https://yanghang0210.github.io/tools/json-diff.html) | 对比两个 JSON 的差异，高亮显示新增、删除、修改的字段 |
| [时间工具](https://yanghang0210.github.io/tools/time.html) | 时间戳转换、日期互转、天/时/分/秒/毫秒时长换算 |
| [URL 编解码](https://yanghang0210.github.io/tools/url.html) | URL 编码/解码，自动保留占位符，智能识别嵌套 URL 参数，解析 URL 结构 |

## 特点

- **纯前端** — 所有计算在浏览器本地完成，数据不上传任何服务器
- **零依赖** — 无第三方框架，单 HTML 文件即可运行
- **暗色主题** — 统一的深色 UI，适合开发者长时间使用
- **响应式布局** — 适配桌面和移动端

## 本地运行

直接用浏览器打开 `index.html` 即可，或使用任意静态文件服务器：

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```

## 项目结构

```
.
├── index.html              # 首页（工具导航）
└── tools/
    ├── json.html           # JSON 格式化/校验/树形视图
    ├── json-diff.html      # JSON 差异对比
    ├── time.html           # 时间戳转换/时长换算
    └── url.html            # URL 编解码
```

## License

MIT

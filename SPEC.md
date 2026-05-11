# 开发工具在线 - 网站规格说明书

## 1. 项目概述

- **项目名称**: 开发工具在线
- **项目类型**: 开发者工具网站（静态HTML）
- **核心功能**: JSON解析、格式化、校验、压缩、转换等在线工具
- **变现方式**: 广告联盟
- **SEO目标**: 百度、谷歌搜索排名优化

## 2. 页面结构

### 2.1 首页布局（从上到下）
```
[顶部导航栏] - Logo + 核心工具入口
[横幅广告位1] - 728x90 顶部横幅
[功能区] - JSON输入框 + 操作按钮 + JSON输出框
[工具卡片区] - 其他工具入口（网格布局）
[横幅广告位2] - 728x90 底部横幅
[底部信息] - 版权、友链、站点地图
```

### 2.2 SEO优化要点
- 每个工具独立一个HTML页面（便于关键词排名）
- 语义化HTML标签（header/nav/main/article/section/footer）
- 完整的meta标签（title/description/keywords/canonical）
- 结构化数据（JSON-LD Schema）
- 生成sitemap.xml

## 3. 核心功能模块

### 3.1 JSON解析格式化
- JSON语法校验
- 格式化/压缩
- 保留/去除转义
- UTF-8/Unicode互换
- JSON语法错误定位

### 3.2 JSON转换工具
- JSON → Java Bean
- JSON → Python Dict
- JSON → JavaScript Object
- JSON → Go Struct
- JSON → TypeScript Interface

### 3.3 其他工具
- 时间戳转换
- URL编解码
- Base64编解码
- Unix时间戳
- 颜色格式转换

## 4. 广告位规划

| 位置 | 尺寸 | 说明 |
|------|------|------|
| 顶部横幅 | 728x90 / 320x100(移动端) | Google AdSense / 百度联盟 |
| 侧边固定 | 160x600 | 侧边栏广告（桌面端） |
| 内容嵌入 | 300x250 | 工具下方信息流广告 |
| 底部横幅 | 728x90 | 页面底部广告 |

## 5. 技术规范

### 5.1 HTML结构
- HTML5语义化标签
- 响应式设计（Bootstrap或纯CSS）
- 代码高亮（Prism.js 或 highlight.js）

### 5.2 性能优化
- CSS/JS 文件压缩
- 图片懒加载
- CDN 加速公共库

### 5.3 SEO优化
- 静态HTML页面
- 自动生成 sitemap.xml
- robots.txt 配置
- Canonical URL
- Open Graph / Twitter Card

## 6. 页面清单

1. `index.html` - 首页/JSON解析
2. `json-format.html` - JSON格式化
3. `json-compress.html` - JSON压缩
4. `json-to-java.html` - JSON转Java
5. `json-to-python.html` - JSON转Python
6. `timestamp.html` - Unix时间戳
7. `url-encode.html` - URL编解码
8. `base64.html` - Base64编解码
9. `color-converter.html` - 颜色格式转换
10. `sitemap.xml` - 站点地图
11. `robots.txt` - 爬虫协议

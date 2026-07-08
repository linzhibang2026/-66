# 🌤️ 晴雨预报 · 实时天气查询

> 一个功能完整、界面优雅的天气预报网页应用，支持中文城市搜索、实时天气展示与未来5天预报。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![OpenWeatherMap](https://img.shields.io/badge/API-OpenWeatherMap-1a6e8f?style=flat-square&logo=openweathermap&logoColor=white)

---

## 📖 项目简介

**晴雨预报** 是一款基于 **OpenWeatherMap** 免费API构建的天气查询工具。用户可以通过输入**中文城市名称**（如“佛山”、“北京”）或使用**浏览器定位**，快速获取当前实时天气和未来5天的天气预报。

### ✨ 核心特性

| 功能 | 描述 |
|------|------|
| 🔍 **城市搜索** | 支持中文/拼音城市名搜索，回车或点击按钮均可触发 |
| 🌡️ **实时天气** | 显示当前温度、天气状况、湿度、风速等详细信息 |
| 📅 **未来预报** | 展示未来5天的最高/最低温度和天气状况 |
| 📍 **定位功能** | 通过浏览器 Geolocation API 自动获取当前位置天气 |
| 💾 **数据持久化** | 使用 localStorage 保存最近搜索的城市，刷新页面自动恢复 |
| 📱 **响应式设计** | 完美适配移动端和桌面端 |

---

## 🖼️ 界面预览

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| **HTML5** | 语义化页面结构 |
| **CSS3** | 磨砂玻璃风格UI + 响应式布局 |
| **JavaScript (ES6+)** | 使用 `async/await`、解构赋值、箭头函数等现代特性 |
| **Fetch API** | 调用 OpenWeatherMap 天气接口 |
| **OpenWeatherMap API** | 免费天气数据源（地理编码 + 实时天气 + 5天预报） |
| **Font Awesome** | 天气图标美化 |

---

## 🚀 快速开始

### 1. 获取 API Key

本项目使用 **OpenWeatherMap** 免费API，您需要先注册并获取密钥：

1. 访问 [OpenWeatherMap 官网](https://openweathermap.org/api) 注册账号
2. 在 Dashboard 中获取您的 **API Key**（免费版每日可调用 1000 次）

### 2. 配置项目

在 `index.html` 中找到以下代码行，替换为您自己的 API Key：

```javascript
const API_KEY = 'bd5e378503939d28ee6b5b9f2f3b8f3b';  // ← 替换为您的 Key

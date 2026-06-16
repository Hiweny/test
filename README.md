# Randomness

随机内容聚合页面 — 汇集多种随机 API，一键获取文案、图片、运势、倒计时等趣味内容。

## 在线访问

[https://hiweny.github.io/meteor-shower](https://hiweny.github.io/meteor-shower)

## 功能特性

- **星空粒子背景**：800 颗粒子 Canvas 动画，支持五角星、十字星、光点、闪耀等多种形态
- **双标签页**：文案（左） / 图片（右），点击切换，卡片抽屉式展开
- **文案自动居中**：展开后内容自动滚动到视口中央
- **星座运势输入框**：支持输入星座名称（如「射手」「射手座」均可识别），自动存储到本地
- **随机色卡**：点击即换色，无需展开，纯色块展示
- **复制 / 下载**：文案卡片支持一键复制，图片卡片支持一键下载

## API 接口

### 文案类（11 个）

| 卡片 | 配色 | API 来源 |
|:---|:---|:---|
| 人生倒计时 | 隙光 | shanhe.kim |
| 星座运势 | 雪岭望 | shanhe.kim（需输入星座） |
| 历史上的今天 | 暮潮 | shanhe.kim |
| 随机抽签 | 赤岩远天 | shanhe.kim |
| 今日诗词 | 海之眼 | jinrishici.com |
| BugPk 一言 | 归港 | api.bugpk.com |
| Hitokoto 一言 | 碧岩 | hitokoto.cn |
| 土味情话 | 樱见 | lovelive.tools |
| 舔狗日记 | 南墙 | shanhe.kim |
| 聚合语录 | 暮卫城 | shanhe.kim |
| 随机色卡 | — | shanhe.kim |

### 图片类（6 个）

| 卡片 | 配色 | API 来源 |
|:---|:---|:---|
| 随机头像 | moon | shanhe.kim |
| 随机 JK 制服 | dusk | shanhe.kim |
| 随机二次元 | snow | shanhe.kim |
| 猫羽雫 | du | shanhe.kim |
| 随机黑丝 | cres | xxapi.cn |
| 随机白丝 | lamp | xxapi.cn |

## 配色方案

新增 10 套「城市与自然」主题配色，每张卡片独立应用：

| 卡片 | 主题 | 主色调 |
|:---|:---|:---|
| 人生倒计时 | 隙光 | 墨林 #192A23 / 暖沙 #D9CCAC |
| 星座运势 | 雪岭望 | 群青 #155693 / 雾蓝 #68A2CD |
| 历史上的今天 | 暮潮 | 墨夜 #171D18 / 深海蓝 #1D6977 |
| 随机抽签 | 赤岩远天 | 远天 #CCD3DC / 赤陶 #D78B5D |
| 今日诗词 | 海之眼 | 黛蓝 #144C5B / 月白 #BDE1EF |
| BugPk 一言 | 归港 | 极夜蓝 #07123E / 冰原灰蓝 #506391 |
| Hitokoto 一言 | 碧岩 | 琉璃青 #1190C1 / 砂白 #DBCFC1 |
| 土味情话 | 樱见 | 朱橘 #D76C27 / 樱云 #E8E3E8 |
| 舔狗日记 | 南墙 | 赤陶 #BA6337 / 象牙白 #F9E8DA |
| 聚合语录 | 暮卫城 | 普鲁士蓝 #33495E / 赭石 #CEAE9C |

## 技术栈

- 纯 HTML/CSS/JavaScript，零依赖
- Canvas 2D 粒子星空背景
- CSS Grid + backdrop-filter 毛玻璃卡片
- localStorage 持久化星座配置
- CORS 受限接口通过 corsproxy.io 代理

## 本地运行

```bash
# 使用任意 HTTP 服务器
python3 -m http.server 8080
# 浏览器打开 http://localhost:8080
```

## License

MIT
# 🌷 Woordenschat — Dutch Flashcard App

自用荷兰语背单词应用。

**访问地址：** https://jjjrce.github.io/dutch-flashcards/

---

## 功能

- **Learn**：三步学习法（选义 → 认句 → 盲测），循环强化直到掌握
- **Review**：间隔重复（SRS）复习，自动安排每日复习计划
- **Spell**：拼写测试，逐字符反馈错误位置
- **《常用》词书**：内置 4594 个荷兰语词汇，覆盖日常使用场景
- 发音朗读（Web Speech API，nl-NL）
- 难词标记与追踪
- 多主题外观（薄荷绿 / 暖米色 / 深夜 / 薰衣草）
- 支持导入自定义词书（CSV / TXT 格式）

## 词条格式

自定义导入支持以下格式（逗号分隔）：

```
荷兰语单词, 词性, 英文释义, 音标, 荷兰语例句, 例句翻译
```

示例：
```
mooi,adjective,beautiful,/moːi/,Wat een mooie dag!,What a beautiful day!
```

## 技术栈

纯 HTML / CSS / JavaScript，无依赖，无框架。学习进度存储在浏览器 localStorage。

## 本地运行

直接用浏览器打开 `woordenschat.html` 即可。

## 更新部署

修改 `woordenschat.html` 后执行：

```bash
git add woordenschat.html
git commit -m "update"
git push
```

1~2 分钟后网站自动更新。

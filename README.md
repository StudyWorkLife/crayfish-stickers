# 🦞 Crayfish 表情包仓库

为OpenClaw的crayfish-sticker技能提供表情包资源，远程托管实时更新。

## 仓库结构
```
├── index.json          # 总索引文件
├── happy/              # 开心分类
├── ok/                 # 收到/同意分类
├── speechless/         # 无语分类
├── sad/                # 难过分类
└── tucao/              # 吐槽分类
```

## 添加新表情
1. 把对应分类的图片放到对应文件夹里
2. 在`index.json`的`stickers`数组里添加新的条目：
```json
{
  "id": "分类_序号",
  "url": "图片raw链接",
  "tags": ["标签1", "标签2", "标签3"]
}
```
3. 提交推送到main分支，所有用户就能自动用到新表情了，不需要更新技能！

## License
MIT

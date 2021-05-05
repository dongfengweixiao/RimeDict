# Rime 拼音词库计划

拟计划建立全新的 Rime 用户词库，本词库具有以下特点：

- 全人工处置（非由网络上流传众多词库简单转换）
- 其他特点暂未知晓

## 词库使用

首先，保证所使用的拼音输入法已经载入扩展词库：

``` yaml
# 以明月拼音为例
# luna_pinyin.custom.yaml
patch:
  "translator/dictionary": luna_pinyin.extended   # 载入扩展词库
```

然后打开 `luna_pinyin.extended.dict.yaml` 按需要启用词库。

选择完毕后重新部署输入法即可。
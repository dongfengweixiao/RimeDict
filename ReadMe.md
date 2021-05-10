# Rime 拼音词库计划

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">知识共享署名-非商业性使用 4.0 国际许可协议</a>进行许可。

拟计划建立全新的 Rime 用户词库，本词库具有以下特点：

- 全人工处置（非由网络上流传众多词库简单转换）
- 其他特点暂未知晓

## 目标

当前，共设置以下几类目标：

### 城市计划（以城市公交地铁站名为主体的词库计划）

1. 城市地铁

    - [x] 北京
    - [ ] 常州
    - [x] 成都
    - [x] 重庆
    - [x] 大连
    - [ ] 东莞
    - [ ] 佛山
    - [ ] 福州
    - [ ] 高雄
    - [x] 广州
    - [ ] 贵阳
    - [ ] 哈尔滨
    - [x] 杭州
    - [ ] 合肥
    - [ ] 呼和浩特
    - [ ] 济南
    - [x] 昆明
    - [x] 兰州
    - [ ] 洛阳
    - [ ] 南昌
    - [x] 南京
    - [ ] 南宁
    - [ ] 宁波
    - [ ] 青岛
    - [x] 厦门
    - [x] 上海
    - [x] 深圳
    - [x] 沈阳
    - [ ] 石家庄
    - [x] 苏州
    - [ ] 台北
    - [ ] 太原
    - [x] 天津
    - [ ] 温州
    - [ ] 乌鲁木齐
    - [ ] 无锡
    - [x] 武汉
    - [x] 西安
    - [ ] 香港
    - [ ] 徐州
    - [ ] 长春
    - [ ] 长沙
    - [ ] 郑州

### 行业计划

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

## 需要你的帮助

此词库的拼音转换完全由《深蓝词库转换工具》完成，故一些词条中的多音字可能并未匹配正确，如有发现，请第一时间告知。


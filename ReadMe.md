# Rime 拼音词库计划

拟计划建立全新的 Rime 用户词库，本词库具有以下特点：

- 全人工处置（非由网络上流传众多词库简单转换）
- 其他特点暂未知晓

## 目标

当前，共设置以下几类目标：

### 城市计划（以城市公交地铁站名为主体的词库计划）

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

# 历史记录

## 2021-05-05 优化 城市计划 - 北京 - 地铁站名

1. 删除词库中所有“xx站”的词条，精简词库。

## 2021-05-05 新增 城市计划 - 天津 - 地铁站名

1. 此词库数据来源于百度百科相关词条
2. 转换由《深蓝词库转换工具完成》
3. 所有站名，都不包括“站”字

## 2021-05-05 新增 城市计划 - 南京 - 地铁站名

1. 此词库数据来源于百度百科相关词条
2. 转换由《深蓝词库转换工具完成》
3. 因为南京某些站点之间使用点号隔开，部分直接分为两个词条
4. 所有站名，都不包括“站”字

## 2021-05-05 新增 城市计划 - 上海 - 公交站名

1. 此词库数据来源于上海公交站牌信息
2. 转换由《深蓝词库转换工具完成》
3. 因上海大量公交站名由xx路yy路的形式构成，为精简词库，这部分全部拆分（中兴路东宝兴路->中兴路，东宝路两个词条）

## 2021-05-05 新增 城市计划 - 上海 - 地铁站名

1. 此词库数据来源于百度百科相关词条
2. 转换由《深蓝词库转换工具完成》
3. 所有站名，都不包括“站”字

## 2021-05-05 新增 城市计划 - 北京 - 公交站名

1. 此词库数据来源于百度百科相关词条
2. 删除所有包含英文和数字的站名
3. 转换由《深蓝词库转换工具完成》
4. 人工调整“十里堡”中“堡”的读音：bao -> pu

## 2021-05-05 新增 城市计划 - 北京 - 地铁站名

1. 此词库数据来源于百度百科相关词条
2. 转换由《深蓝词库转换工具完成》
3. 人工调整“十里堡”中“堡”的读音：bao -> pu
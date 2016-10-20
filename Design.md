#大纲

###关于卡牌设计
卡牌设计采用xml格式，基本格式如下：

```
<!--卡牌模板示例-->
    <?xml version="1.0" encoding="UTF-8"?>
    <card>
        <!--角色id-->
        <id>0</id>
        <!--角色名称-->
        <name>Test</name>
        <!--角色属性-->
        <attr>光</attr>
        <!--角色成长属性列表-->
        <growlist>
        <grow>
            <level>1</level>
            <hp>10</hp>
            <atk>5</atk>
        </grow>
        <grow>
            <level>2</level>
            <hp>16</hp>
            <atk>8</atk>
        </grow>
        ...
        </growlist>
    </card>
```


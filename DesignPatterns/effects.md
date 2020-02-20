# 特效示例

## 流程图

```flow
st=>start: 陪妹子进商场
op=>operation: 买买买
cond=>condition: 妹子开不开心?
e=>end: 出商场
st->op->cond
cond(yes)->e
cond(no)->op
```

## 序列图

```sequence
战士->领导: 首长好
Note right of 领导: 首长复杂的内心活动
领导-->战士: 同志们好
战士->>领导: 为人民服务
```

## 类图

``` mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```



Welcome to the algorithm wiki!

只是测试

{% chart %}
{
    "data": {
        "type": "bar",
        "columns": [
            ["data1", 30, 200, 100, 400, 150, 250],
            ["data2", 50, 20, 10, 40, 15, 25]
        ],
        "axes": {
            "data2": "y2"
        }
    },
    "axis": {
        "y2": {
            "show": true
        }
    }
}
{% endchart %}
ddddddd

{% chart %}
{
    "xAxis": {
        "type": "category",
        "data": ["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]
    },
    "tooltip": "{}",
    "yAxis": {
        "type": "value"
    },
    "series": [{
        "data": [820, 932, 901, 934, 1290, 1330, 1320],
        "type": "line"
    }]
}
{% endchart %}

sssssss

{% chart %}
{
    "data": {
        "type": "bar",
        "columns": [
            ["data1", 30, 200, 100, 400, 150, 250],
            ["data2", 50, 20, 10, 40, 15, 25]
        ],
        "axes": {
            "data2": "y2"
        }
    },
    "axis": {
        "y2": {
            "show": true
        }
    }
}
{% endchart %}

{% graph %}
{
    "title": "1/x * cos(1/x)",
    "grid": true,
    "xAxis": {
        "domain": [0.01, 1]
    },
    "yAxis": {
        "domain": [-100, 100]
    },
    "data": [{
        "fn": "1/x * cos(1/x)",
        "closed": true
    }]
}
{% endgraph %}

```chart
{
    "title": {
        "text": "Fruits number"
    },
    "tooltip": {},
    "legend": {
        "data":["Number"]
    },
    "xAxis": {
        "data": ["Apple","Banana","Peach","Pear","Grape","Kiwi"]
    },
    "yAxis": {},
    "series": [{
        "name": "Number",
        "type": "bar",
        "data": [5, 20, 36, 10, 10, 20]
    }]
}
```

{% chart %}
{
    "title": {
        "text": "Fruits number"
    },
    "tooltip": {},
    "legend": {
        "data":["Number"]
    },
    "xAxis": {
        "data": ["Apple","Banana","Peach","Pear","Grape","Kiwi"]
    },
    "yAxis": {},
    "series": [{
        "name": "Number",
        "type": "bar",
        "data": [5, 20, 36, 10, 10, 20]
    }]
}
{% endchart %}

Code mode:

```chart
{
    "width": "900px",
    "height": "500px",
    "title": {
        "text": "Fruits number"
    },
    "tooltip": {},
    "legend": {
        "data":["Number"]
    },
    "xAxis": {
        "data": ["Apple","Banana","Peach","Pear","Grape","Kiwi"]
    },
    "yAxis": {},
    "series": [{
        "name": "Number",
        "type": "bar",
        "data": [5, 20, 36, 10, 10, 20]
    }]
}
```
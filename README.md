# 1 数组

## 简单方法

| 方法名 | 作用 | 格式 | 案例 |
| :--- | :--- | :--- | :--- |
| push | 在数组末尾添加元素 | arr.push\(element1, ..., elementN\) | \[1,2,3\].push\(4\) |
| pop | 删除数组末尾的一个元素 | arr.pop\(\) | \[1,2,3\].pop\(\) |
| unshift | 在数组起始位置添加元素 | arr.unshift\(element1, ..., elementN\) | \[1,2,3\].unshift\(0\) |
| shift | 删除数组其实位置的一个元素 | arr.shift\(\) | \[1,2,3\].shift\(\) |
| slice | 返回被截取的数组，左闭右开\[ \)，不改变原数组 | arr.slice\(\[begin\[, end\]\]\) | \[1,2,3\].slice\(0,1\) |
| concat | 连接2个或多个数组，并返回结果数组 | var new\_array = old\_array.concat\(value1\[, value2\[, ...\[, valueN\]\]\]\) | arr1.concat\(,0,1,\[1,2,3\],arr2\) |
| join | 将数组中的每个元素按照一定的样式隔开，并返回一个字符串 | arr.join\(\[separator\]\) | arr.join\(' - '\) |
| reverse | 将数组中元素的位置颠倒 | arr.reverse\(\) | arr.reverse\(\) |
| some |  |  |  |

## 重要方法

### splice

作用：

对数组的特定位置进行 增、删、改 等操作

格式：



Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}




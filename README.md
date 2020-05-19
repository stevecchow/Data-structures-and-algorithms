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

**作用：**

对数组的特定位置进行 增、删、改 等操作

**格式：**

```javascript
array.splice(start[, deleteCount[, item1[, item2[, ...]]]])
```

**参数：**

* start：指定要操作的元素位置
* deleteCount：要删除的元素个数（可选，不选为删除自start开始后面的所有）
* item1,item2,...：待插入的元素（可选，不选代表不插入）

**返回值：**

被删除的元素所构成的数组

**案例：**

```javascript
let arr = [1,2,3,4,5]
arr.splice(2,2,100,101,102) // 返回 [3, 4]
console.log(arr)	// [ 1, 2, 100, 101, 102, 5 ]
```

### 

### every

**作用：**

判断数组中的所有元素，是否全部符合某一标准

**格式：**

```javascript
arr.every(callback[, thisArg])
```

**参数：**

* callback：用来测试每个元素的函数，它可以接受三个参数
  * element：用于测试的当前值
  * index：当前值的索引（可选）
  * array：当前数组（可选）

**返回值：**

如果回调函数的每一次返回都为真值，返回 true ，否则返回 false。

**案例：**

```bash
let arr = [1,2,3,4,5]
// 结果：return false，因为 arr 中的元素不都大于 3
arr.every(x => {
  return x>3
})
```




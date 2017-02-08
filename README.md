# READMERule
## README.md语法规则
### 一、换行
代码：<br>
```
段落1<br>段落2

段落3
```
效果：<br>
段落1<br>
段落2

段落3

### 二、标题
Setext形式：= 大标题  - 中标题<br>
atx形式：#<br>
代码：<br>
```
大标题
======
中标题
------
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题 
```
效果：<br>
大标题
======
中标题
------
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题 

### 三、区块
代码：<br>
```区块
>区块1
>>区块2
>>>区块3
```
效果：<br>
>区块1
>>区块2
>>>区块3

### 四、强调
\*强调\* 或者 \_强调\_  (示例：斜体)<br>
\*\*加重强调\*\* 或者 \_\_加重强调\_\_ (示例：粗体)<br>
\*\*\*特别强调\*\*\* 或者 \_\_\_特别强调\_\_\_ (示例：粗斜体)<br>
代码：
```
*强调*<br>
_强调_<br>
**强调**<br>
__强调__<br>
***强调***<br>
___强调___<br>
```
效果：<br>
*强调*<br>
_强调_<br>
**强调**<br>
__强调__<br>
***强调***<br>
___强调___<br>

### 五、列表
代码：（注意：* + - 前后加空格，tab键或四个空格可分级）
```
* 列表1
 + 列表2
   - 列表3
```
效果：<br>
* 列表1
 + 列表2
   - 列表3

### 六、链接
代码：
```
[百度一下-你就知道](http://www.baidu.com "百度一下")
```
效果：<br>
[百度一下-你就知道](http://www.baidu.com "百度一下")

### 七、图片：![]( "title")
代码：
```
![baidu.png](http://www.baidu.com "百度图片")
```
效果：<br>
![baidu.png](http://www.baidu.com "百度图片")

### 八、代码 ：$ <> 会被自动的转换成 HTML 实体
代码：
```
`
代码代码代码
代码代码代码
`
```
效果：<br>
`
代码代码代码
代码代码代码
`
<br>
代码：
```
实际没有前后的\
 \```
 代码代码代码
 代码代码代码
 \```
```
```
代码代码代码
代码代码代码
```
要建立一个已经格式化好的代码区块，只要每行都缩进 4 个空格或是一个 tab 就可以了。

最后，注意反斜杠\实现转义效果。

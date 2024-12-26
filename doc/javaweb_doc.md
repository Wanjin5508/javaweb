# Java Web 黑马

web开发 的常规工作流
![img.png](img.png)

**重点关注**: 服务器端和数据库

## agenda
共20天左右

注意这里的part6 两种部署方式
![img_1.png](img_1.png)

了解详细的项目开发流程, 严格前后段分离

![img_3.png](img_3.png)

![img_4.png](img_4.png)

HTML: 网页的元素
CSS: 布局
JS: 动作和行为


# Part 1 前段开发 HTML(结构) + CSS(样式)
![img_5.png](img_5.png)

![img_6.png](img_6.png)


查找 前端三剑客 标签列表和用途:
![img_7.png](img_7.png)

img 需要的属性是 文件目录.
![img_10.png](img_10.png)

_HTML标签不区分大小写!_



## JS 

![img_11.png](img_11.png)

### JS 的引入方式
![img_12.png](img_12.png)
![img_13.png](img_13.png)

JS 标签不能自闭合, 必须使用 开头和结尾 tag

![img_14.png](img_14.png)

**输出语句**:
![img_15.png](img_15.png)

原来 JS  也是动态类型语言!
![img_16.png](img_16.png)
--> 然后使用前面的输出方法, 将变量输出!

![img_17.png](img_17.png)
全局变量表示, 我们可以从大括号外面取到该变量

![img_18.png](img_18.png)
下面的赋值会覆盖上一个


![img_19.png](img_19.png)

![img_21.png](img_21.png)
![img_22.png](img_22.png)


![img_23.png](img_23.png)


![img_24.png](img_24.png)
![img_25.png](img_25.png)

### 类型转换
![img_27.png](img_27.png)
![img_26.png](img_26.png)


### 流程控制
![img_28.png](img_28.png)

### JS  函数
![img_29.png](img_29.png)
![img_30.png](img_30.png)

![img_31.png](img_31.png)

### JS 对象

- 3 个基础对象: Array, String, JSON
- 浏览器对象: BOM, (封装了浏览器对象)
- DOM - HTML 标签被封装成了对象

  ![img_32.png](img_32.png)

#### Array

Array类似JAVA 的集合 : 长度可变, 类型可变
![img_33.png](img_33.png)
![img_34.png](img_34.png)
![img_35.png](img_35.png)
![img_36.png](img_36.png)
foreach 循环只遍历有值的元素, 普通for循环便利所有元素

![img_37.png](img_37.png)
![img_38.png](img_38.png)
==> 箭头函数类似 java 的lambda表达式

删除元素: (从第几个索引位置开始, 删除几个元素)
![img_39.png](img_39.png)


#### String

![img_40.png](img_40.png)

string的属性和方法

![img_41.png](img_41.png)


![img_42.png](img_42.png)


### JS 自定义对象

![img_43.png](img_43.png)

自定义对象包含方法, 注意两种定义方法的方式:
![img_44.png](img_44.png)

### JSON

key必须使用双引号!

前后段交互使用json, 请求复杂数据

![img_45.png](img_45.png)

![img_46.png](img_46.png)

![img_47.png](img_47.png)


### BOM

![img_48.png](img_48.png)

![img_49.png](img_49.png)

![img_50.png](img_50.png)

![img_51.png](img_51.png)


设定定时器:
![img_52.png](img_52.png)

截止时间, 仅执行一次
![img_53.png](img_53.png)


![img_54.png](img_54.png)

获取当前地址, 然后重新定向到新地址: 
![img_55.png](img_55.png)

### DOM
**使用DOM 操作, 修改原始HTML 文档的内容和格式**

![img_56.png](img_56.png)

![img_57.png](img_57.png)

![img_58.png](img_58.png)

--> HTML DOM 是核心DOM 的子集, 将所有HTML标签封装成了对象

![img_59.png](img_59.png)

4种获取元素的方法实现:
![img_60.png](img_60.png)


#### DOM 案例

![img_61.png](img_61.png)


![img_62.png](img_62.png)

1. 点亮灯泡
实际上是通过id替换图片

2. 修改html标签

![img_63.png](img_63.png)

灵活利用标签对象的属性

3. 勾选 复选框

![img_64.png](img_64.png)


### JS 事件监听

![img_65.png](img_65.png)

![img_66.png](img_66.png)

![img_67.png](img_67.png)

![img_68.png](img_68.png)

还是html牛逼阿, table的起始标签居然这么长!!:

![img_69.png](img_69.png)

#### JS 事件监听案例

原始页面:
![img_70.png](img_70.png)

![img_71.png](img_71.png)

![img_72.png](img_72.png)

![img_73.png](img_73.png)


## Vue - 一个高级前端框架

![img_74.png](img_74.png)

双向数据绑定, 类似 MVC 设计模式, 当模型和视图中的一个发生改变, 则另一个同步发生改变.

双向绑定不需要手动实现, 而是依靠框架














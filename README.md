# Markdown Study
For more detials, see [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
## 1.标题
'''井号+空格'''
### 示例
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
### 代码
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
## 2.代码
'''行内代码用一对`(Esc下面那个符号)；代码块用一对```，开始的三个符号后面标注语言'''
### 示例
比如说我这个句子里面有一个行内代码`print (hello world)`没错前面就是一个行内代码
```python
pip install numpy
pip install opencv_python
```
### 代码
```
比如说我这个句子里面有一个行内代码`print (hello world)`没错前面就是一个行内代码
```python
pip install numpy
pip install opencv_python
```(不用管这个括号里的内容，是为了让前面的```可以显示)
```
## 3.引用
'''大于号+空格'''
### 示例
> 这是一个引用内容
### 代码
```
> 这是一个引用内容
```
## 4.序列
'''星号或减号或加号+空格'''
### 示例
* li1
  * li1li1
    * li1li1li1
- li2
  - li2li1
    - li2li1li1
+ li3
  + li3li1
    + li3li1li1
### 代码
```
* li1
  * li1li1
    * li1li1li1
- li2
  - li2li1
    - li2li1li1
+ li3
  + li3li1
    + li3li1li1
```
## 5.倾斜，加粗，删除，分割线
'''两端加一颗星，两端加两颗星，两端加三颗星，两端加~~是删除，---或***是一条分割线'''
### 示例

*倾斜*  

**加粗**   

***倾斜且加粗***   

~~删除~~   

---
***
### 代码
```
*倾斜*
**加粗**
***倾斜且加粗***
~~删除~~
---
***
```
## 6.表格
'''用|来划分表格，用|-|:-|:-:|-:|这些调整位置'''
### 示例
|col1|col2|col3|col4|
|-|:-|:-:|-:|
|默认左对齐|左对齐|居中|右对齐|
### 代码
```
|col1|col2|col3|col4|
|-|:-|:-:|-:|
|默认左对齐|左对齐|居中|右对齐|
```
## 7.链接和图片
### 示例
[动物所地址](http://www.ioz.cas.cn/)
### 代码
```
[动物所地址](http://www.ioz.cas.cn/)
![某图片](../img/md/md.jpg)
```
## 8.折叠
### 示例
<details>
  <summary>View contents</summary>

  - li1
  - li2
  - li3
  - li4
    
</details>

### 代码
```
<details>
  <summary>View contents</summary>

  - li1
  - li2
  - li3
  - li4
    
</details>
```
## 9.注意
`markdown` 一般换行要行末空三格，或者直接空一行










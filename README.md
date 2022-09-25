# Markdown 簡易編輯器

> 為 [JOBALL找專家](https://joball.tw) / [UMD你的博客](https://umd.tw) 的需求所開發的編輯器<br>用於提供給用戶們撰寫內容的編輯器<br><br>md語法未完全適配，後續會更新補強<br><br>開發者: [Pardn Chiu](https://github.com/pardnchiu)

##### 引用

- 圖示: [Font Awesome 5.15.4 Free](https://fontawesome.com/v5/search "Font Awesome 5.15.4 Free")

- 高亮: [Google Code-Pretty](https://github.com/googlearchive/code-prettify "Google Code-Pretty")

<br>

##### 需自行實現

- 上傳圖片

<br>

##### 功能介紹

###### 字體

# 標題1

## 標題2

### 標題3

#### 標題4

##### 標題5

###### 標題6

**粗體(*)**
__粗體(_)__
<b>粗體(html)</b>
*斜體*
<em>斜體(html)</em>
***粗斜體(*)***
__*粗斜體(_)*__
<b><em>粗斜體(html)</em></b>
<br>
###### 引用
> 這是一段引用的註解<br>這是一段引用的註解<br>這是一段引用的註解
<br>
###### 圖片
| 圖片(寬160) | 圖片(高120) | 圖片+標題 | 圖片+連結 |
| - | - | - | - |
| ![](./image/pardn.svg =160*) | ![](./image/pardn.svg =*120) | ![Pardn Chiu](./image/pardn.svg "Pardn Chiu" =120*120) | [![](./image/pardn.svg =120*120)](https://github.com/pardnchiu "Pardn Chiu") |
<br>
###### 連結
| 連結+標題 | 直接連結 |
| - | - |
| [Github](https://github.com/pardnchiu "Github") | https://github.com/pardnchiu |
<br>
###### 表格
| 標題1 | 標題2 | 標題3 |
| - | - | - |
| 內容1 | 內容2 | 內容3 |
| 內容4 | 內容5 | 內容6 |
| 內容7 | 內容8 | 內容9 |
<br>
###### 五、程式碼
***・ 單列***
`const test = 123;`
***・ 多列***
```
function test1 () {
    console.log('123')
};
```
***・ 縮排多列 (空白鍵 * 4／Tab * 1)***
    function test2 () {
        console.log('123')
    };

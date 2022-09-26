# Markdown 簡易編輯器
> 為 [JOBALL找專家](https://joball.tw) / [UMD你的博客](https://umd.tw) 需求所開發的功能
用來提供給用戶們撰寫內容的編輯器
md語法未完全適配，後續會更新補強
僅展示的前端功能，若有上傳圖片需求，請自行搭配後台
開發者: [Pardn Chiu](https://github.com/pardnchiu)


##### 引用
- 圖示: [Font Awesome 5.15.4 Free](https://fontawesome.com/v5/search "Font Awesome 5.15.4 Free")
- 高亮: [Google Code-Pretty](https://github.com/googlearchive/code-prettify "Google Code-Pretty")

##### 預覽
| index |
| - |
| ![image](/preview/index.png =100%*) |

#### 頂部按鈕
```
<script>
  var mdEditorConf = {
    nav: {
      // 自訂圖示
      logo : String,
      // 自訂標題
      title: String,
      buttons: {
        // 移除標題
        removeHeading: Boolean,
        // 添加標題1
        addHeading1: Boolean,
        // 添加標題2
        addHeading2: Boolean,
        // 添加標題3
        addHeading3: Boolean,
        // 添加標題4
        addHeading4: Boolean,
        // 添加標題5
        addHeading5: Boolean,
        // 添加標題6
        addHeading6: Boolean,
        // 添加粗體
        addBold: Boolean,
        // 添加刪除線
        addStrikeThrough: Boolean,
        // 添加斜體
        addItalic: Boolean,
        // 添加引用區塊
        addBlockQuote: Boolean,
        // 添加無序列表
        addUnorderList: Boolean,
        // 添加有序列表
        addOrderList: Boolean,
        // 添加代碼區塊
        addCodeBlock: Boolean,
        // 添加連結
        addLink: Boolean,
        // 添加圖片
        addImage: Boolean,
        // 清除全部
        eraseAll: Boolean,
        // 下載檔案 (md)
        downloadMd: Boolean,
        // 下載檔案 (html)
        downloadHtml: Boolean,
        // 開啟檔案 (md)
        openMd: Boolean
      }
    }
  };
</script>
```

##### 需自行實現

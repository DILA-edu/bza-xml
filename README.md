# 別譯雜阿含專案 XML 及使用說明

這是[別譯雜阿含專案](http://buddhistinformatics.dila.edu.tw/BZA)的 XML 檔使用說明。

# 取得 xml

這個倉庫的 XML 來自[別譯雜阿含專案](http://buddhistinformatics.dila.edu.tw/BZA) 右邊功能表最下面的「下載壓縮檔」。

# 小經清單及對照表

上述壓縮檔解開後，在根目錄有一個 [comCatBza.xml](comCatBza.xml)，  
這個 xml 檔裡是一個大 list，裡面就是許多小經的清單及對照，例如其中的一部小經如下：

```xml
<list xml:id="bza001" type="cluster" n="001">
  <head xml:lang="en">Sujāta is praised</head><!-- 這部小經的英文標題 -->
  <head xml:lang="zh">善生二種端嚴</head><!-- 這部小經的中文標題 -->
  <item n="bza" xml:lang="zh"><!-- zh 表示 中文 -->
    <ref target="bza001.xml">
      <seg type="short">別譯雜阿含</seg>
      <seg type="detailed">bza001</seg>
    </ref>
  </item>
  <item>
    <ref target="bza001eng.xml">
      <seg type="short">BZA English</seg>
      <seg type="detailed">別譯雜阿含英譯</seg>
    </ref>
  </item>
  <item n="za" xml:lang="zh">
    <ref target="b001za1062.xml">
      <seg type="short">雜阿含</seg>
      <seg type="detailed">za1062</seg>
    </ref>
  </item>
  <item xml:lang="pi"><!-- pi 表示 巴利文 -->
    <ref target="b001snSujato.xml">
      <seg type="short">SN</seg>
      <seg type="detailed">SN,II,278 (Sujāto)</seg>
    </ref>
  </item>
</list>
```

上面 ref 元素的 target 屬性就是這部小經的各異本 XML 檔，放在 xml 資料夾下面。

xml:lang 屬性值參考 [ISO 639-2](http://www.loc.gov/standards/iso639-2/php/code_list.php)

# xml

小經 xml 檔各元素說明詳見 [doc/elements](doc/elements) 資料夾。

# div (division)

文本區段

## type="opening"

經文開頭，相當於「序分」：

```xml
<div type="opening" xml:id="obza001">
  <p n="bza001.01">如是我聞：一時佛在<name type="place">彌絺羅國</name>
    <name type="place">菴婆羅園</name>。</p>
</div>
```

## type="main"

經文主體

```xml
<div type="main" xml:id="mbza001">
  <p n="bza001.02">爾時尊者<name type="person">善生</name>初始出家，剃除鬚髮，來詣佛所，頂禮佛足，在一面坐。佛告諸比丘：</p>
  <q who="gotamo">
    <p n="bza001.03">此族姓子善生有二種端嚴：一、容貌<app n="fnT02p0374n06">
        <lem wit="【大】">璝</lem>
        <rdg resp="Taisho" wit="【宋】【元】【明】">傀</rdg>
      </app>璝偉，天姿挺特。二、能剃除鬚髮，身服法衣，深信家法會歸無常，出家學道；盡諸煩惱，具足無漏，心得解脫，慧得解脫；身證無為，生死永盡，梵行已立，不受後有。</p>
  </q>
  <p n="bza001.04">佛說是已，即說偈言：</p>
  <q who="gotamo">
    <lg n="bza001.05" met="5" xml:id="cg001a">
      <l>比丘常寂定<caesura/>除欲離生死</l>
      <l>住最後邊身<caesura/>能破於魔軍</l>
      <l>修心斷諸結<caesura/>端正無等倫</l>
    </lg>
  </q>
</div>
```

## type="closing"

經文結尾，相當於「流通分」：

```xml
<div type="closing" xml:id="cbza001">
  <p n="bza001.06">佛說是<app n="fnT02p0374n07">
      <lem wit="【大】">經</lem>
      <rdg resp="Taisho" wit="【宋】【元】【明】"/>
    </app>經已，諸比丘聞佛所說，歡喜奉行。</p>
</div>
```

## type="parallel"

例如 b001snSujato.xml，意思可能是平行版本。
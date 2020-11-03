Float 排版

block, inline-block

https://www.w3schools.com/html/html_blocks.asp
/

兩種 clear fix 用法

1.在下一個 DIV 做 clear

https://codepen.io/easonliu913/pen/BaKpvVM

2.在父層 DIV 做 clear

https://codepen.io/easonliu913/pen/OJNWror

/
Grid 排版方法

Grid-template-columns: 定義容器有多少欄 (給寬度值)

Grid-template-rows: 定義容器有多少列 (給高度值)

display:grid;

grid-template-columns: 240px auto;

Grid-template-rows: 100px 200px 1fr;

其實就是類似表格的排版感覺，但是長寬設定更加彈性了。

注意： 設定除了 px 之外，還有 1fr 與 auto 的關係。

Row-gap, Column-gap, Gap: 設定欄位之間的距離
/
Flex: flex-basis
主軸為橫向的時候：
Flex-basis 其實就是決定 items 在放進 flex 容器時的寬度。

如果沒給 flex-basis，則預設值為 auto，寬度取決於 width 的設定。

如果沒給 width 設定，則寬度由內容決定。

注意：flex-basis 值會受到 max-width / min-width 影響。
/

嘗試用 Flex 切版

所有排列屬性都學完，

現在試著用 Flex 來挑戰排版吧

https://alameda-demo.squarespace.com/

/

CSS column 用法

.container {
column-count: 3;
column-rule:
}

/
排版四要素:
1.控制內部距離padding
2.控制外部距離margin
3.控制字的間距letter-spacing
4.控制字的行高line-height

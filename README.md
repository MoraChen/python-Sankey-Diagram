# Sankey Diagram 桑基圖 是一個能綜觀全局流向的圖

有的，那就是 Sankey Diagram 桑基圖，就是這麼一種可以全面展現流向的圖表。它的源頭可追溯到1898年，愛爾蘭人Matthew Henry Phineas Riall Sankey在土木工程師學會會報中首度提出了這種能量流動圖，因此得名。在一個桑基圖愛好者的社區網站上，我們可以看到這麼一句話：「A Sankey diagram says more than 1000 pie charts」，意謂著一張桑基圖的描述力超越了一千張餅圖，由此可見，桑基圖對於複雜數據的視覺化表現力非凡，它的功能和使用場景與餅圖有部分重合。

#如何畫出金錢的流向圖?

我們將使用 Google Colab（Google 的雲端程式碼執行環境）來實現資料視覺化和製作桑基圖（Sankey Diagram），流程包含以下幾個步驟：

1. 在 Google 雲端建立一個資料夾並將記帳的 CSV 檔案放入。

2. 連接 Colab 到這份共享的 CSV 檔案資料集。

3. 在 Google Colab 中設定中文字體。

4. 與 ChatGPT 互動，清晰地說明需求，讓 ChatGPT 提供完整的程式碼。

5. 利用 Plotly 來呈現消費支出流向的桑基圖。

# Platform 13｜咖啡館小時光

以店內照片與補充位置說明重建的互動 3D 咖啡館，使用 Three.js 與 WebGL2。

[開啟展示](https://rolanthhuang.github.io/Platform13/) · [內側水槽與洗碗空位](https://rolanthhuang.github.io/Platform13/?v=kitchen15#kitchenOvens) · [櫃檯](https://rolanthhuang.github.io/Platform13/?v=kitchen15#counter)

[下載 Cloudflare Pages v15 更新包](cloudflare-pages-v15.zip)

目前版本為 v15：保留照片位置的主水槽，以及油炸機右側、懸吊架附近的第二個窄水槽；調整烤箱架，留出能從工作走道抵達的洗碗操作空位。

- 烤箱架移向另一側，保留兩層四台設備與原本尺寸，讓水槽旁有獨立空位。
- 操作空位不擺放櫃體或垃圾桶；垃圾桶收在內槽下方。原本會與烤箱架重疊的櫃角檯面移除，小型咖啡包展示移至前端櫃檯角落。
- 主水槽、瀝水籃、鬆餅機、電磁爐與油炸機維持原位置；兩槽盆深一致。
- 「洗碗區」觀看角度可直接檢查內槽旁的空位。其他觀看、試擺、光線與 4K 下載功能保留。

## 使用與檔案

`index.html` 已內嵌程式、樣式與展示貼圖，不需要額外安裝或建置。以靜態網頁伺服器開啟即可；瀏覽器需支援 WebGL2。

`cloudflare-pages-v15.zip` 解壓後根目錄為同一份 `index.html`，可用於 Cloudflare Pages。先前的 [v14 更新包](cloudflare-pages-v14.zip) 與 [v13 更新包](cloudflare-pages-v13.zip) 仍保留。

`THREE-LICENSE.txt` 為 Three.js 授權聲明。

## 範圍

水槽旁需要站立操作空位是參考提供者的補充；設備間距與遮蔽處尺寸仍為推估，未經現場丈量。原始參考照片保留於本機，未隨此次更新上傳。

座位與貓咪沿用先前版本；貓咪頭部仍為 v13 試修，臉型與神情尚未達到參考照片的相似度。

網頁 SHA-256：`22c494d3d9e45ff007b847c4b3ce74ee12511c5a61480d020dc0af19ce85c1c0`。

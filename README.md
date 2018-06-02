# 呂家華大戰波波獸！

Chia-Hua Lu v.s. Proposal! Live at: http://chiahua0515.github.io/

## 新增轉址頁面的步驟

1. 在跟目錄開一個新的檔案
    - 登入 GitHub 並打開 https://github.com/ChiaHua0515/ChiaHua0515.github.io 這一頁
    - 按下 `Create new file` 按鈕
    - 在檔名的地方輸入資料夾名稱，也就是想給別人的網址的最後一段，比如說想給別人 `chiahua0515.github.io/blulu` 這個網址的話，資料夾名稱就取做 `blulu`
    - 確定資料夾名稱無誤後，按下 `/`
    - 接著輸入 `index.html` 也就是檔案名稱
2. 編輯新增的 `index.html` 檔案
    - 複製 https://github.com/ChiaHua0515/ChiaHua0515.github.io/blob/master/blulu/index.html 的內容
    - 把 `og_title: "Blulu"` 的 `Blulu` 改成分享此網址時想給別人預覽時的標題文字。比如說想讓別人在收到網址時顯示的預覽標題為 `能源轉型`，這一行就要改成 `og_title: "能源轉型"`
    - 同理，如果有英文標題的話，把 `og_title_en:` 這一行改成 `og_title_en: "Your English Title"` ，沒有英文標題的話則不動
    - 把 `redirect: "https://blulu.tw"` 這一行裡面的 `https://blulu.tw` 換成你想讓別人前往的網址，比方說，想讓別人從這頁自動導向到 `https://hackmd.io/c/rJSNT8Xyb` 的話，就寫成 `redirect: "https://hackmd.io/c/rJSNT8Xyb"`
    - 如果沒有要自訂網址預覽顯圖的話，把 `og_image: "image.png"` 的 `"image.png"` 刪掉讓這一欄留空，也就是變成只剩下 `og_image:`
    - 按下頁面下方 `Commit new file` 按鈕
4. （選擇性）如果想自訂這一頁的網址預覽顯圖的話
    - 在你的電腦的 Finder 或檔案總管中，把想上傳的圖檔檔名改成 `image`
    - 在剛才新開的資料夾的畫面中，按下 `Upload files` 按鈕
    - 把想上傳的圖檔拖進去後，按 `Commit changes` 按鈕完成上傳
    - 上傳後在資料夾畫面中檢查圖檔的副檔名，如果不是 `png` 的話，去步驟 2. 開的 `index.html` 檔案中，把 `og_image: "image.png"` 的 `png` 改成你的檔案的副檔名（通常圖片檔的副檔名不是 `png` 就是 `jpg`），改完一樣按 `Commit changes` 存檔
5. 完成～

## 新增首頁資料的步驟

1. 登入 GitHub 並打開 https://github.com/ChiaHua0515/ChiaHua0515.github.io/blob/master/_data/projects.yml 這個檔案
2. 按鉛筆按鈕編輯，格式抄現有的範本即可，改完按 `Commit changes` 成功後首頁的列表就會更新了

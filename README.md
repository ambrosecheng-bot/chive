# 韭菜俱樂部 · 2026 年度同行之書 🌱

> Chive Club — 2026 Annual Plan Website
>
> 「種植不只發生在泥土裡,也發生在人與人之間。」

這是 **韭菜俱樂部(Chive Club)** 2026 年度發展計劃的單頁網站(single-page website),把一整年的同行願景化為一段流暢的捲動敘事。專案以「**互相支援、分享成果、關懷社群**」為核心,服務 Southampton 的香港移民社群。

🔗 **網站線上版(Live site):** https://ambrosecheng-bot.github.io/chive/

---

## 關於專案 · About

韭菜俱樂部是一個以後院種植為起點的社群互助計劃 —— 透過共耕、共食與知識共享,讓一群初學園藝的家庭彼此扶持、一起成長。這個網站是 2026 年度發展計劃的數位呈現,既是對外的介紹,也是社群成員的共同願景書。

本網站為純靜態網頁(static HTML),**毋須任何建置工具或後端**,可直接以 GitHub Pages 免費部署。

---

## 三大發展主軸 · Three Pillars

| 主軸 | 英文 | 核心精神 |
|------|------|----------|
| **互助種植** | Mutual Gardening | 你不是一個人在種 |
| **從土地到餐桌** | Farm to Table | 把成果變成記憶 |
| **知識與資源共享** | Sharing & Learning | 一起少走冤枉路 |

---

## 網站章節 · Page Sections

網站以年度計劃的章節為框架,由上而下依序為:

1. **年度定位** — Hero 主視覺與一句話定位
2. **年度宗旨(Purpose)** — 互相支援 / 分享成果 / 關懷社群
3. **三大發展主軸** — 互助種植、Farm to Table、知識共享
4. **社群延伸與外展(Giving Back)** — 義賣、送贈、祝福延伸
5. **年度運作原則** — 不寫成規則的三條默契
6. **四季行動** — 春播、夏長、秋收、冬整
7. **年度願景** — 結尾呼籲與祝福

---

## 本地預覽 · Run Locally

本專案為純靜態網頁,直接用瀏覽器開啟即可:

```bash
# 方法一:直接開啟
open index.html          # macOS
# 或在檔案總管 double-click index.html(Windows)

# 方法二:啟動本地伺服器(建議,圖片載入較穩定)
python3 -m http.server 8000
# 然後在瀏覽器開啟 http://localhost:8000
```

---

## 部署到 GitHub Pages · Deploy

1. 把本專案的所有檔案(`index.html` 與 `images/` 資料夾)推送到 GitHub repo。
2. 進入 repo 的 **Settings → Pages**。
3. 在 **Source** 選擇 `Deploy from a branch`,Branch 選 `main`(資料夾選 `/ (root)`),按 **Save**。
4. 等待約 1 分鐘,GitHub 會提供網址。本專案的網址為 `https://ambrosecheng-bot.github.io/chive/`。

> 💡 **提示:** 確保 `index.html` 位於 repo 的根目錄(root),GitHub Pages 才能正確找到首頁。

---

## 檔案結構 · Project Structure

```
.
├── index.html              # 網站主檔(內嵌 CSS / JS,單一檔案)
├── images/                 # 全部相片素材(共 14 張)
│   ├── hero_garden.jpg         # Hero 主視覺:後院共耕
│   ├── purpose_seeding.jpg     # 年度宗旨:一起播種
│   ├── mutual_planting.jpg     # 主軸一:互助種植
│   ├── f2t_harvest.jpg         # 主軸二:收成的喜悅
│   ├── f2t_share.jpg           # 主軸二:共享的時光
│   ├── f2t_preserve.jpg        # 主軸二:傳承的味道
│   ├── sharing_tools.jpg       # 主軸三:知識與資源共享
│   ├── givingback_banner.jpg   # 社群外展橫幅
│   ├── principles_gather.jpg   # 運作原則:社群聚會
│   ├── season_spring.jpg       # 四季:春
│   ├── season_summer.jpg       # 四季:夏
│   ├── season_autumn.jpg       # 四季:秋
│   ├── season_winter.jpg       # 四季:冬
│   └── vision_banner.jpg       # 年度願景結尾橫幅
└── README.md
```

---

## 技術說明 · Tech Notes

- **純靜態(Static):** 只有 HTML / CSS / JavaScript,無框架、無建置步驟、無相依套件。
- **字型(Fonts):** Noto Serif TC(標題)、Noto Sans TC(內文),透過 Google Fonts 載入。
- **色系(Palette):** 暖橙 `#E8722A`、深棕 `#4A2C17`、米白 `#F5EDD6`、草綠 `#7A9E5A`。
- **互動(Interaction):** 捲動漸現、隨捲動「發芽生長」的左側軸線、響應式版面(桌面與手機)。
- **無障礙(Accessibility):** 支援鍵盤焦點、`prefers-reduced-motion`(尊重使用者的減少動態設定)。

若要更換圖片,直接以同名檔案覆蓋 `images/` 內對應的檔案即可,無需改動 `index.html`。

---

## 圖片來源 · Image Credits

網站相片取自韭菜俱樂部 2026 年度發展計劃簡報,記錄社群的真實活動(共耕、收成、共食與聚會)。圖片版權屬韭菜俱樂部及其成員所有,僅供本社群非商業用途使用。

---

## 授權 · License

本專案內容供韭菜俱樂部社群非商業用途使用。如需轉用程式碼或圖片,請先聯絡專案維護者。

---

## 聯絡 · Contact

韭菜俱樂部(Chive Club)· Southampton community gardening initiative

如有查詢、想加入社群或參與共耕,歡迎透過社群的 WhatsApp 群組聯絡我們。

---

<div align="center">

*「凡你手所當作的事,要盡力去作。」— 傳道書 9:10*

Made with 🌱 by 韭菜俱樂部

</div>

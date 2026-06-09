# 上野匠 炭火燒肉職人 — 網頁試玩版

## 直接試玩
打開 `index.html` 即可在瀏覽器預覽。

## 目前功能
- 四種定稿關卡：烤五花肉飯、烤雞腿飯、烤里肌肉飯、烤排骨飯
- 使用原始生鮮肉 PNG 與原始出餐 PNG 素材
- 烤網熟度變化：生肉、半熟、完美、烤焦
- 翻面提示：返せ！翻面！
- 夾進便當盒
- 完美出餐畫面與抽獎券

## LINE LIFF 串接
請到 LINE Developers 建立 LIFF App 後，把正式網址填入 LIFF Endpoint URL。
接著可在 game.js 加入 LIFF SDK 與登入流程。

建議正式部署：Vercel / Netlify / Cloudflare Pages。
如需每日限玩、抽獎核銷，需要加後端 API + 資料庫。

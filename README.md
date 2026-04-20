# taiwan-body-fat-standards

台灣體脂肪標準資料庫。收錄依性別、年齡分類的體脂肪率健康範圍、台灣衛福部與
ACSM 標準比較、常見體脂肪測量方法的準確度評估，以及內臟脂肪與代謝風險的關聯。

## 為什麼建立這個資料庫

台灣採用亞洲人適用的體脂肪標準（衛福部，2014），與歐美 ACSM/WHO 標準不同。
同樣 BMI 25 的亞洲人，體脂肪比例和內臟脂肪通常高於歐美族群，因此代謝風險
切點不同。本資料庫整理台灣適用的體脂肪標準，以及各種測量方法的實用說明。

## 資料說明

| 檔案 | 說明 |
|------|------|
| `data/body-fat-ranges.json` | 依性別、年齡分類的體脂肪率健康範圍（台灣衛福部 vs ACSM 標準） |
| `data/measurement-methods.json` | 各種測量方法比較（BIA、皮脂夾、DEXA、水中秤重） |
| `data/visceral-fat.json` | 內臟脂肪指標與代謝風險（腰圍、腰臀比、腰高比） |

## 資料來源

- 衛福部國民健康署健康體重管理計畫（2014）
- ACSM's Guidelines for Exercise Testing and Prescription, 10th ed. (2018)
- Deurenberg P et al. (2002) Asia Pac J Clin Nutr. PMID: 12022029（亞洲 BMI 體脂差異）
- Wang J et al. (1994) Am J Clin Nutr. PMID: 8172101（體脂肪測量）
- WHO Expert Consultation (2004) Lancet. PMID: 14728096（亞洲 BMI 切點）

## 相關工具

燃脂研究所 BMI 計算工具：[metabolab.tw/calculators/bmi](https://metabolab.tw/calculators/bmi)

---

本資料庫為教育用途，不構成醫療建議。體脂肪評估與減脂計畫請諮詢醫師或運動營養師。

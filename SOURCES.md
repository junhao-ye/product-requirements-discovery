# 來源與採用決策

## 原始材料

以下三張圖由使用者隨需求提供，作為本 Skill 的主要依據。保留圖中的順序、方法及欄名。問句、交付格式和範例為依據這些材料設計的實作。

| 原始材料 | 採用內容 | 對應位置 |
|---|---|---|
| 圖片 1（五層漏斗及補充要求） | 目標 → 場景 → 流程 → 邊界 → 驗收。將右側 11 種方法放進指定層次逐一執行，每個方法都有問句與回填結果。 | [五層工作流](SKILL.md) |
| 圖片 2（十二種手法） | 蘇格拉底六問、Mom Test、第一性原理、5 Whys、XY 問題、Kano 雙問、逆向思維、失敗預演、極端情況、現地現物、魔鬼代言人、費曼複述。 | [十二種提問法](references/question-methods.md) |
| 圖片 3（每項功能的九件事） | 觸發、現狀、輸入、輸出、判斷標準、邊界、異常、優先級、來源。 | [九欄標準](SKILL.md#每個功能點的九件事) |

## 格式與方法補充

- 以 Agent Skills 正式規範為格式依據。採用小寫連字號名稱、YAML frontmatter、相對路徑及按需載入參考資料。依本機「skill-writer」的撰寫流程建立維護規格與結構驗證。 [Agent Skills Specification](https://agentskills.io/specification)
- Shape Up 採用先定投入、再收斂本期範圍的做法。 [Basecamp《Shape Up》](https://basecamp.com/shapeup/1.2-chapter-03)
- MoSCoW 採用以本期交付時間窗為基準的四級取捨。 [Agile Business Consortium](https://www.agilebusiness.org/resource/what-is-moscow-prioritization/)
- 驗收採 Given、When、Then，並把 Then 寫成使用者或下游能觀察的結果。 [Cucumber Gherkin Reference](https://cucumber.io/docs/gherkin/reference/)
- Mom Test 採用具體案例與中性訪談來取得現況。Kano 採用成對問題收集偏好，結果再與成本、依賴及交付承諾共同決定優先級。 [Rob Fitzpatrick《The Mom Test》](https://www.momtestbook.com/)、[Kano 等〈Attractive Quality and Must-Be Quality〉](https://www.jstage.jst.go.jp/article/quality/14/2/14_KJ00002952366/_article/-char/en)
- 蘇格拉底六問以釐清概念、假設、證據、觀點、後果與問題本身六個角度，改寫成產品訪談問句。 [Paul 與 Elder 的蘇格拉底提問指引](https://www.criticalthinking.org/pages/steps-of-critical-thinking/480)

## 設計與覆蓋

| 採用決策 | 涵蓋的情況 |
|---|---|
| 採有參考檔的逐步工作流程。五層、九欄與完成條件放在主檔，問法選擇及案例依工作進度載入。 | 降低初始閱讀量，維持五層順序，讓各種執行環境能以相同檔案運作。 |
| 建立框架時，依圖逐層使用對應方法，記錄結論與依據或待確認問題。 | 可從最終框架查回每種方法得到的資訊。已有資料可直接回答，缺口以對應問法釐清。 |
| 功能澄清的十二種問法按缺口和證據選用。每個功能一律核對九欄，訪談預設一次集中問 1–3 題。 | 資料完整可直接成稿，資料缺漏可分輪訪談，跨功能的共同規則可以引用同一證據。 |
| 記錄依據、決策分歧及待確認狀態。來源有變化時回查受影響的上游層級。 | 支援規則衝突、風險高的例外、範圍變更及處理到一半的需求交接。 |
| 用同一個虛構產品示範正常推進、分歧與修正方案先行。 | 可直接對照五層框架、九欄功能卡、驗收案例和下一個追問。 |

三張圖足以確定固定順序、各層的提問方法、功能澄清的問法及逐項欄位。補充資料用於核對術語的用法和套件結構。問句、判定門檻及範例可隨使用回饋迭代。

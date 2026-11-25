# 產品需求梳理 Skill

**繁體中文** · [简体中文](README.zh-CN.md) · [English](README.en.md) · [日本語](README.ja.md)

把產品點子、訪談筆記或既有 PRD，整理成可評審、可驗收的需求。先按五層漏斗建立產品框架，再用十二種問法逐項釐清功能卡的九個欄位。

## 在 Codex 快速開始

1. 解壓套件，將整個 `product-requirements-discovery` 資料夾放進 Codex 的自訂 Skill 目錄。這個目錄通常是 `~/.codex/skills`。有自訂路徑時，依[安裝與啟用說明](USAGE.md#安裝與啟用)找到對應位置。
2. 在新對話選取 `$product-requirements-discovery`，貼上下面這段指令試用。也可以換成自己的題目並附上現有資料。

~~~text
$product-requirements-discovery
我想做公司內部會議室的自助預約，目前常有兩個人訂到同一時段。
請依五層漏斗訪談我，先產出框架，再逐項問清本期功能。
~~~

## 會拿到什麼

- **產品框架**　依目標、場景、流程、邊界、驗收五層排列，每層呈現對應方法得到的結論與依據。
- **功能清單與九欄功能卡**　每個功能有 ID、對應流程、優先級，以及可追溯的欄位結論。
- **驗收案例與待確認事項**　用 Given–When–Then 寫前提、事件和可觀察結果，並列出仍需取得的答案或決議。
- **Markdown PRD**　要求產出 PRD 時，套用固定章節，將框架、功能規格、跨功能需求、驗收和決策紀錄整合成一份文件。

## 套件內容

| 檔案 | 用途 |
|---|---|
| [使用說明書](USAGE.md) | 安裝步驟、可複製指令、訪談方式與交付檢查。 |
| [SKILL.md](SKILL.md) | Skill 的工作流程、問句和完成條件。 |
| [專用 PRD 模板](assets/prd-template.md) | 單份 PRD 的章節、九欄功能卡、驗收與來源紀錄。 |
| [十二種提問法](references/question-methods.md) | 功能欄位有缺口時，選擇適合的追問。 |
| [會議室預約案例](references/worked-example.md) | 對照五層框架、功能卡與驗收案例。 |
| [維護規格](SPEC.md)與[來源紀錄](SOURCES.md) | 觸發範圍、驗證方式及方法來源。 |

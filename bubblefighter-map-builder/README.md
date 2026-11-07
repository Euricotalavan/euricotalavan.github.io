# 泡泡建造工具 · 靜態版本紀錄

公開網站只含人工整理的版本摘要，不包含遊戲資源、私人診斷、電腦路徑或可執行檔。

## 更新
1. 編輯 `releases.json`，在陣列最前方新增版本。未知日期填 `null`，不要補猜。
2. `items.kind` 使用 `new`（新增）、`fix`（修正）、`change`（調整）。
3. 在 `limit` 寫清楚尚待驗證的事項，勿將離線測試當成遊戲驗收。
4. 執行 `python build.py`，將資料生成完整靜態 `index.html`。
5. 提交此目錄到 GitHub Pages 所在分支。網站不需要Node、套件、後端或API金鑰。

預覽：在 repository 根目錄執行 `python -m http.server 8768`，開啟 `/bubblefighter-map-builder/`。

首頁使用相對路徑，可搬到其他GitHub Pages repository或靜態主機。原站首頁未修改。
歷史摘要依保留的使用說明與驗證紀錄回溯，日期不完整的版本明確標記。

# 2026thanksgivingday
###請將目前的「幸福+感謝故事館」改為以 Google Forms 作為同仁留言及抽獎資料來源，Google Sheets 作為資料庫。
【活動流程】
同仁透過 LINE@ 進入幸福+感謝故事館。
點擊「我要分享感謝」按鈕，開啟指定 Google Forms。
同仁填寫今年想感謝的人、感謝原因、感恩小故事及抽獎資料。
Google Forms 自動將回覆寫入 Google Sheets。
HR 在 Google Sheets 審核故事是否公開。
已核准的感謝故事自動同步至幸福+感謝故事館。
同仁點擊故事卡片，即可閱讀完整故事 Modal。
【資料庫規劃】
Google Sheets 建立以下工作表：
Form Responses：Google Forms 原始回覆。
Public Stories：網站公開感謝故事。
Lottery Data：抽獎名單及領獎資料。
網站只能讀取 Public Stories 中已核准且同意公開的故事。
不得讀取 Form Responses 或 Lottery Data 的個人資料。
【網站修改】
新增「我要分享感謝」按鈕，連結 Google Forms。
新增「感謝故事審核中」的說明文字。
新增「幸福+感謝故事館」資料來源提示。
故事卡片點擊後，開啟完整故事 Modal。
匿名留言不可顯示姓名、部門或其他識別資訊。
網站增加「抽一份幸福」功能，隨機展示已核准的感謝故事。
網站增加感謝故事總數統計，數字依實際公開故事資料計算。
【Google Apps Script】
請建立完整 Apps Script：
讀取 Public Stories 工作表。
僅回傳已核准及同意公開的故事。
故事內容需包含 ID、分類、標題、完整內容、公開作者及日期。
不可回傳抽獎資料、員工編號、電子郵件或其他個人資料。
API 僅提供唯讀公開故事資料。
請提供部署為 Web App 的操作說明。
請確保 API 可以供 GitHub Pages 網站讀取。
【GitHub】
請直接提供完整的一段專案程式碼，而不是只提供範例片段。要可以直接貼在github上的程式碼

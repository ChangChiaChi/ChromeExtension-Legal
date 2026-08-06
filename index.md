---
title: Markdown Viewer Pro Privacy Policy
---

# Markdown Viewer Pro 隱私權政策

**最後更新：2026 年 8 月 6 日**

Markdown Viewer Pro 由 Thunder Studio 提供，只處理使用者選擇預覽的本機或網頁 Markdown／文字內容，以及主題、字體大小與目錄側邊欄狀態。

解析、DOMPurify 清理、KaTeX 與 Mermaid 都在瀏覽器本機執行。使用者按下「預覽目前分頁」後，網頁 Markdown 會以單次 request ID 暫存在 `chrome.storage.session`，Viewer 讀取後立即刪除；未完成的資料最遲在瀏覽器工作階段結束時清除。偏好設定保留在 Extension `localStorage`，直到使用者清除網站資料或解除安裝。

擴充功能不會把文件文字、網址或偏好設定傳送給 Thunder Studio，不含分析、廣告或遙測。若文件引用遠端圖片，Chrome 可能直接向該圖片來源發出請求以顯示資源，但不會把文件文字附加到請求中。

我們不會出售、分享或移轉使用者資料，不會將資料用於廣告、信用評估或與 Markdown 預覽無關的用途，也不允許人員閱讀文件內容。

Markdown Viewer Pro 對 Chrome API 資訊的使用遵守 Chrome Web Store User Data Policy，包括 Limited Use 要求。資料只用於提供或改善已揭露的 Markdown 預覽功能。

資料刪除方式：session 文件在 Viewer 讀取後刪除，最遲在瀏覽器工作階段結束時清除；偏好設定可透過清除 Extension 網站資料或解除安裝刪除。

問題或刪除請求請使用 [Markdown Viewer Pro Support](https://github.com/ChangChiaChi/ChromeExtension-Legal/issues)。

## English

**Last updated: August 6, 2026**

Markdown Viewer Pro is provided by Thunder Studio. It handles only the local or web Markdown/text content that a user chooses to preview, plus local theme, font-size, and sidebar preferences.

Parsing, DOMPurify sanitization, KaTeX, and Mermaid rendering run locally in the browser. Web Markdown selected through **Preview current tab** is held under a one-time request ID in `chrome.storage.session`, removed immediately after the Viewer consumes it, and otherwise cleared when the browser session ends. Preferences remain in Extension `localStorage` until the user clears Extension site data or uninstalls the Extension.

The Extension does not transmit document text, URLs, or preferences to Thunder Studio and includes no analytics, advertising, or telemetry. Chrome may fetch remote images referenced by a document directly from their source so they can be displayed; document text is not appended to those requests.

We do not sell, share, or transfer user data, use it for advertising, credit decisions, or unrelated purposes, or permit humans to read document content.

Markdown Viewer Pro's use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Data is used only to provide or improve the disclosed Markdown preview feature.

Web document session data is deleted after the Viewer consumes it and otherwise at the end of the browser session. Preferences can be deleted by clearing Extension site data or uninstalling Markdown Viewer Pro.

For questions or deletion requests, use [Markdown Viewer Pro Support](https://github.com/ChangChiaChi/ChromeExtension-Legal/issues).

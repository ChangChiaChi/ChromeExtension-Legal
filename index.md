---
title: Markdown Viewer Pro Privacy Policy
---

# Markdown Viewer Pro 隱私權政策

**最後更新：2026 年 10 月 14 日**

Markdown Viewer Pro 由 Thunder Studio 提供，只處理使用者選擇預覽的本機或網頁 Markdown／文字內容與來源網址，以及主題、字體大小與目錄側邊欄狀態。

解析、DOMPurify 清理、KaTeX 與 Mermaid 都在瀏覽器本機執行。使用者按下「預覽目前分頁」後，網頁 Markdown 的單次交接資料會以 request ID 暫存在 `chrome.storage.session`，Viewer 讀取後立即刪除該交接資料；未完成的交接資料最遲在瀏覽器工作階段結束時清除。

為支援重新整理，Viewer 另將目前預覽文件與來源網址保留在擴充功能來源、每分頁獨立的 `sessionStorage`，與來源網站隔離。每個分頁只保留目前預覽，新預覽會取代舊暫存。重整暫存依瀏覽器分頁工作階段保留，可能隨瀏覽器工作階段復原而恢復；清除 Extension 網站資料可移除。前述立即刪除僅指單次交接資料。重整暫存不會寫入 `localStorage` 或傳送至伺服器。

主題、字體大小與目錄側邊欄偏好設定保留在 Extension `localStorage`，直到使用者清除 Extension 網站資料或解除安裝。

擴充功能不會把文件文字、網址或偏好設定傳送給 Thunder Studio，不含分析、廣告或遙測。若文件引用遠端圖片，Chrome 可能直接向該圖片來源發出請求以顯示資源，但不會把文件文字附加到請求中。

我們不會出售、分享或移轉使用者資料，不會將資料用於廣告、信用評估或與 Markdown 預覽無關的用途，也不允許人員閱讀文件內容。

Markdown Viewer Pro 對 Chrome API 資訊的使用遵守 Chrome Web Store User Data Policy，包括 Limited Use 要求。資料只用於提供或改善已揭露的 Markdown 預覽功能。

資料刪除方式：單次交接資料在 Viewer 讀取後刪除，最遲在瀏覽器工作階段結束時清除。每分頁重整暫存會由新預覽取代，並可透過清除 Extension 網站資料移除；瀏覽器工作階段復原可能恢復該暫存。偏好設定可透過清除 Extension 網站資料或解除安裝刪除。

問題或刪除請求請使用 [Markdown Viewer Pro Support](https://github.com/ChangChiaChi/ChromeExtension-Legal/issues)。

## English

**Last updated: October 14, 2026**

Markdown Viewer Pro is provided by Thunder Studio. It handles only the local or web Markdown/text content and source URLs that a user chooses to preview, plus local theme, font-size, and sidebar preferences.

Parsing, DOMPurify sanitization, KaTeX, and Mermaid rendering run locally in the browser. Web Markdown selected through **Preview current tab** is handed off under a one-time request ID in `chrome.storage.session`. That handoff entry is removed immediately after the Viewer consumes it, and otherwise cleared when the browser session ends.

To support reload, the Viewer separately retains the current preview document and source URL in extension-origin, per-tab `sessionStorage`, isolated from the source website. Only the current preview is retained per tab; a new preview replaces the previous cache. The reload cache follows the browser tab-session lifetime and may be restored by browser session recovery. Clearing Extension site data removes it. Immediate deletion above refers only to the one-time handoff. The reload cache is not written to `localStorage` or sent to a server.

Theme, font-size, and sidebar preferences remain in Extension `localStorage` until the user clears Extension site data or uninstalls the Extension.

The Extension does not transmit document text, URLs, or preferences to Thunder Studio and includes no analytics, advertising, or telemetry. Chrome may fetch remote images referenced by a document directly from their source so they can be displayed; document text is not appended to those requests.

We do not sell, share, or transfer user data, use it for advertising, credit decisions, or unrelated purposes, or permit humans to read document content.

Markdown Viewer Pro's use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Data is used only to provide or improve the disclosed Markdown preview feature.

The one-time handoff entry is deleted after the Viewer consumes it and otherwise at the end of the browser session. The per-tab reload cache is replaced by a new preview and can be removed by clearing Extension site data; browser session recovery may restore the cache. Preferences can be deleted by clearing Extension site data or uninstalling Markdown Viewer Pro.

For questions or deletion requests, use [Markdown Viewer Pro Support](https://github.com/ChangChiaChi/ChromeExtension-Legal/issues).

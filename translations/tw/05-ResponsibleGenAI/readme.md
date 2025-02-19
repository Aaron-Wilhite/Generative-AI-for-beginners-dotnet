# 負責任地使用生成式 AI

生成式 AI 提供了強大的功能，但確保這些應用是倫理、公平且安全的至關重要。本課程將探討如何將負責任的 AI 原則有效地融入 .NET 應用程式中。

---

## 負責任的 AI 原則

在開發生成式 AI 解決方案時，請遵守以下原則：

1. **公平性**：確保 AI 模型對所有用戶一視同仁，避免偏見。
2. **包容性**：設計 AI 系統以適應多元化的用戶群體和場景。
3. **透明性**：清楚地告知用戶何時正在與 AI 互動，以及其數據的使用方式。
4. **責任性**：對 AI 系統的結果負責，並持續進行監控。
5. **安全與隱私**：透過強大的安全措施和合規性保護用戶數據。

如需更詳細的說明，請參考這篇 [負責任地使用生成式 AI 課程](https://github.com/microsoft/generative-ai-for-beginners/tree/main/03-using-generative-ai-responsibly)。

## 為什麼要優先考慮負責任的 AI？

優先考慮負責任的 AI 實踐可以確保信任、合規性和更好的結果。以下是主要原因：

- **幻覺現象**：生成式 AI 系統可能產生事實錯誤或語境不相關的輸出，這種現象被稱為幻覺。這些不準確性可能削弱用戶的信任並影響應用的可靠性。開發者應使用驗證技術、知識基礎方法和內容限制來解決此挑戰。

- **有害內容**：AI 模型可能無意間生成冒犯性、偏頗或不恰當的內容。若缺乏適當的審核，這些內容可能對用戶造成傷害並損害聲譽。像 [Azure AI Content Safety](https://azure.microsoft.com/products/ai-services/ai-content-safety/) 這樣的工具對於有效過濾和減輕有害輸出至關重要。

- **缺乏公平性**：生成式 AI 可能放大訓練數據中的偏見，導致對個人或群體的不平等對待。解決這一問題需要對數據進行仔細審核、使用像 [Fairlearn](https://fairlearn.org/) 這樣的工具進行公平性評估，以及持續監控以確保公平結果。

- **法律合規**：滿足如 GDPR 這樣的監管要求，減輕法律風險。

- **聲譽管理**：避免倫理陷阱並確保公平使用以維持信任。

- **商業利益**：倫理 AI 能夠建立用戶信任，提升用戶留存率和採用率。

## 如何負責任地使用生成式 AI

遵循以下步驟，確保在 .NET 中負責任地實施生成式 AI 解決方案：

### 審核數據來源

- 審查並改進訓練數據以避免偏見和不準確性。
- 示例：使用像 [Fairlearn](https://fairlearn.org/) 這樣的工具來評估公平性。

### 實施反饋機制

- 允許用戶標記問題或對模型輸出提供修正意見。

### 整合內容審核功能

- 使用像 [Azure AI Content Safety](https://azure.microsoft.com/products/ai-services/ai-content-safety/) 這樣的工具過濾不恰當的內容。

### 確保模型安全

- 加密敏感數據並使用像 [Microsoft.Identity.Web](https://github.com/AzureAD/microsoft-identity-web) 這樣的庫強制實施身份驗證。

### 測試邊界情況

- 模擬多樣化的場景，包括對抗性和不尋常的輸入，以確保系統的穩健性。

### 考慮倫理因素

- 通過告知用戶他們何時正在與 AI 互動來確保透明性。
- 定期更新模型以反映倫理標準和社會規範。
- 與多元化的利益相關者交流，了解 AI 系統的廣泛影響。

### 持續監控

- 實施持續監控以檢測和減輕偏見和不準確性。
- 使用自動化工具持續評估 AI 模型的性能和公平性。
- 定期審查用戶反饋，並根據需要進行調整以改進系統。

## 結論與資源

在 .NET 應用程式中負責任地實施生成式 AI 對於確保倫理、安全和無偏見的結果至關重要。通過遵循公平性、包容性、透明性、責任性和安全原則，開發者可以構建值得信賴的 AI 系統，為用戶和社會帶來益處。

> 🙋 **需要幫助嗎？**：如果您遇到任何問題，請在倉庫中提交問題。

## 其他資源

利用以下工具來實施負責任的 AI 實踐：

- [Fairlearn](https://fairlearn.org/): 評估並解決公平性問題。
- [Fairlearn - A Python package to assess AI system's fairness](https://techcommunity.microsoft.com/blog/educatordeveloperblog/fairlearn---a-python-package-to-assess-ai-systems-fairness/1402950)
- [Azure AI Content Safety](https://azure.microsoft.com/products/ai-services/ai-content-safety/): 有效審核內容。
- [Azure AI Services](https://azure.microsoft.com/products/cognitive-services/): 構建符合倫理的 AI 解決方案。
- [Microsoft Learn - Responsible AI](https://learn.microsoft.com/training/modules/embrace-responsible-ai-principles-practices/): 探索負責任的 AI 實踐。
- [Microsoft Responsible AI](https://www.microsoft.com/ai/responsible-ai): 了解 Microsoft 如何實踐負責任的 AI。

**免責聲明**：  
本文件使用基於機器的人工智能翻譯服務進行翻譯。我們雖然努力確保翻譯準確，但請注意，自動翻譯可能會包含錯誤或不精確之處。應以原文文件作為權威來源。對於關鍵資訊，建議使用專業人工翻譯。我們對於使用此翻譯所引起的任何誤解或錯誤解釋概不負責。
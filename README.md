# Medical Diagnosis Assistant RAG

## 專案目標

本專案設計一個基於 RAG（Retrieval-Augmented Generation）的醫療診斷輔助系統，協助使用者根據症狀查詢可能疾病與相關建議。

## 系統特色

* 結合向量資料庫與大型語言模型（LLM）
* 提供可解釋答案（附資料來源）
* 降低 hallucination 問題

## 技術

* Embedding: BGE-M3
* Vector DB: FAISS
* LLM: OpenAI / LLaMA
* 評估: RAGAS

## 系統流程

1. 使用者輸入症狀
2. 系統轉為向量
3. 搜尋相關醫療資料（Top-K）
4. Reranking
5. LLM 生成回答

## 注意事項

本系統僅供學術用途，不可作為醫療診斷依據

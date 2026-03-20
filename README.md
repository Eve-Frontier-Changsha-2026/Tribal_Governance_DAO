# 專案名稱：Tribal_Governance_DAO (部落憲章與領地治理系統)

> 📜 **[EVE Frontier 專案憲法與開發準則](https://github.com/Eve-Frontier-Changsha-2026/Constitution/blob/master/EVE_Frontier_Project_Constitution.md)**
> 本專案的世界觀設定與底層相依資源，均遵從此憲法文檔之規範。


## 📌 概念簡介
針對 EVE 中強大的公會政治與領土控制，我們結合 Sui 的多簽 (Multi-sig) 與安全存取控制機制，建立了一套透明且自動化的「聯盟治理憲章 (On-chain Charter)」。將所有權約定、徵稅制度、外交戰略落實到星門、精煉廠與據點防禦網的程式碼內，形成星際領主的實質約束力。

## 🎯 解決痛點與核心循環
- **領地存取控制 (Access Control)**：基於鏈上憑證或 NFTs 動態管理 Smart Assemblies（如砲塔、防護網、倉庫）的使用權限，自動拒絕黑名單人物進出。
- **共同國庫與稅收分配**：這不是單純 UI 投票系統。領地產生資源時，扣除設定稅率進入公庫自動分潤，並在鏈上記錄透明勞資結果與戰功分享。
- **外交條約的硬性執行**：對經過的玩家徵收過路費；把互不侵犯條約 (NAPs) 白紙黑字上鏈，違約自動沒收保證金或標記通緝，賦予叢林法則一點法治。

## 🔗 與 Sui / World Contracts 的結合
- Charter 本身以 Sui 物件實作，紀錄所有治理參數（V1、V2...），任何修改需經 on-chain 多簽或議會投票通過後執行。
- 透過 World Contracts 控制防禦塔邏輯：只有憲章載明的白名單角色可操作基地，並且無縫連動稅率調整、過路費閘門邏輯。
- 結合 zkLogin 機制，參與投票治理就像收信一樣簡單，不需所有後勤玩家精通區塊鏈底層。

## 🏆 得獎潛力
- **高度原生體驗**：社群與治理組織向來是最具代表性的「文明工具」，此計畫將空泛的 DAO 具體化到了星際設施。
- **創造永恆歷史**：每次政變、分裂、結盟、黑吃黑的歷史，都會永遠烙印在鏈上。
- **突顯 Sui 能力**：深植入遊戲物理機制的 Smart Assemblies，徹底展現 Web3 Game 的所有權與規則革命。

## 🤝 衍生/相關專案參考
- **[Bounty_Escrow_Protocol](../Bounty_Escrow_Protocol)**：本專案國庫將運用此協議發布「DAO 後勤任務 (Bounty for Logistics)」，自動提撥資金獎勵運送指定物資的成員。


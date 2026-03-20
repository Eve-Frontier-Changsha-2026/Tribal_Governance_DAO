# Tribal Governance DAO — 開發計畫

> 層級：應用層
> 定位：部落憲章 + 領地設施 ACL + 外交條約

---

## 架構定位

```
Tribal Governance DAO ──依賴──▶ Bounty Escrow Protocol（後勤任務）
                      ──整合──▶ Explorer Hub（領地預警系統，訂閱熱力圖）
```

---

## 開發階段

### Phase 1：Charter Object 合約
- [ ] Charter 定義為 Sui Object（部落憲章）
- [ ] 多簽 / 鏈上投票修改機制
- [ ] 領地設施 ACL 綁定（防禦塔、精煉廠、星門）

### Phase 2：外交 & 執行
- [ ] NAP 條約合約（違反自動沒收保證金 / 標記通緝）
- [ ] 稅收分配機制
- [ ] 政變 / 分裂 / 結盟事件永久鏈上記錄

### Phase 3：治理前端
- [ ] 提案 / 投票 UI
- [ ] 條約管理介面
- [ ] 領地設施存取控制面板

### Phase 4：跨專案整合
- [ ] 與 Bounty 整合：後勤任務發布（物資運輸、設施維修）
- [ ] 與 Explorer Hub 整合：DAO 國庫訂閱熱力圖作為預警系統

---

## 技術待確認
- [ ] Charter Object 的 abilities 與生命週期
- [ ] 多簽方案（原生 multisig? 自建?）
- [ ] 稅收自動分配的觸發機制

---

## TODO
- [ ] Charter Object 合約架構設計
- [ ] 治理前端 scaffold
- [ ] UI 串接 Bounty 後勤任務

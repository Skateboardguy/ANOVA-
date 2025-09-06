# ANOVA- 相關膨脹因子VIF檢定

```mermaid
flowchart TD
A[模型診斷與驗證]
   B--> [檢查殘差常態性、變異數齊一性]
   C--> [檢查多重共線性 (VIF)]
   D--> [若為預測 → 做交叉驗證]
   E--> [若為解釋 → 檢查 η², R², Adj-R²]


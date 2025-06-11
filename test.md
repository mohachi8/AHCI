---
marp: false
---

<style>
/* フォントサイズやノードの余白を調整 */
.mermaid .node text {
  font-size: 22px;
}
.mermaid .node rect {
  padding: 20px 40px;
}
</style>

## 行為遂行のサイクル

```mermaid
flowchart TD
    A[ゴールの形成] --> B[意図の形成]
    B --> C[行為の詳細化]
    C --> D[行為の実行]
    D --> E[外界の状況の知覚]
    E --> F[外界の状況の解釈]
    F --> G[結果の評価]
    G -->A
 ```
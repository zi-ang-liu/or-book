```{mermaid}
flowchart LR
    A[旅行先の選択]
    subgraph 評価基準
        B1[気候]
        B2[食事]
        B3[費用]
    end
    subgraph 代替案
        C1[北海道]
        C2[沖縄]
        C3[九州]
    end
    A --> B1
    A --> B2
    A --> B3
    B1 --> C1
    B1 --> C2
    B1 --> C3
    B2 --> C1
    B2 --> C2
    B2 --> C3
    B3 --> C1
    B3 --> C2
    B3 --> C3

    style 評価基準 fill:#eee
    style 代替案 fill:#eee
```
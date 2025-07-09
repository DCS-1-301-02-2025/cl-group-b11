# ○○の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]
    
    八王子国際キャンパス -> 高尾駅[label=バス]
    高尾駅 -> 西国分寺駅[label=中央線]
    西国分寺駅 -> 北朝霞駅・朝霞台駅[label=武蔵野線]
    北朝霞駅・朝霞台駅 -> 成増駅[label=東武東上線]
    成増駅 -> 山﨑自宅[label=徒歩]
}
```

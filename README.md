# travel_plan — 米井家 旅行アーカイブ

家族旅行の**計画**と**振り返り**を、旅行ごとに積み重ねていくリポジトリです。

## 🌐 公開ページ（GitHub Pages）

**https://pp-lib.github.io/travel_plan/**

トップページが旅行一覧のハブになっています。各旅行の「計画」「振り返り」へそこから移動できます。

> 更新が反映されない場合はブラウザをハードリロード（Mac: `Cmd+Shift+R` ／ Windows: `Ctrl+Shift+R`）してください。

## 📁 構成

```
travel_plan/
├── index.html                        … 旅行一覧ハブ（トップページ）
├── README.md                         … このファイル（台帳）
└── trips/
    ├── 2026-summer-japan/
    │   ├── plan.html                 … 計画（フライト・カレンダー・地図・宿・費用など）
    │   └── retrospective.md          … 振り返り（持ち物哲学・教訓）
    └── 2027-spring-lebaran/
        ├── plan.html                 … 計画（フライト・行程・休日マップ・30日カレンダー・手配リスト）
        ├── tokyo.html                … 東京内 詳細乗り継ぎマップ（別ページ）
        └── retrospective.md          … 振り返り（旅行後に記入）
```

## 🗂️ 旅行一覧

| 旅行 | 期間 | 計画 | 振り返り |
|------|------|------|----------|
| 2026年夏 日本旅行 | 2026/7/25〜8/2 | [plan.html](trips/2026-summer-japan/plan.html) | [retrospective.md](trips/2026-summer-japan/retrospective.md) |
| 2027年春 レバラン休暇 日本旅行（東京→四国中央市・計画中） | 2027/3/6〜4/4 | [plan.html](trips/2027-spring-lebaran/plan.html) | [retrospective.md](trips/2027-spring-lebaran/retrospective.md) |

## ➕ 新しい旅行を追加するには

1. `trips/YYYY-季節-行き先/` フォルダを作成（例：`trips/2027-winter-hokkaido/`）
2. その中に `plan.html`（計画）と `retrospective.md`（振り返り）を置く
3. `index.html` の「旅行一覧」にカードを1枚追加し、上の表にも1行足す

## 📖 持ち物・パッキングの原則

次回準備の起点として、[2026年夏の振り返り](trips/2026-summer-japan/retrospective.md) に持ち物・軽量化の原則を体系化しています（「入れ物より荷物を減らす」「季節・コースで組み替える」「預け入れを賢く使う」など）。

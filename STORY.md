# Day033 Story — Triage Flow Board 1

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day033専用にテーマをseed固定して再生成時の見た目を安定化
- devtools用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: workflow_triage
- Mechanic: board_flow
- Input/Output: board_items -> board
- Audience Promise: relief
- Publish Hook: カードの組み合わせから次の試作案を素早く作るデッキ型ツール。（話題:GitHub Trending (A） を visual_demo 角度で見せる
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day033｜流れ見直しボード
作業の流れのつまる場所を見つけるためのツールです。

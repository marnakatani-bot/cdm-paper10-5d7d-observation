# まりあ研究ノート｜論文⑩（公開準備キット）

**著者：中谷まり亜（Maria Nakatani）**  
**状態：DRAFT v0.1（2026-11-16）／GitHub公開・事前登録は未実施**

「意識の次元マッピング」論文⑨「鏡面構造」から続く、5次元と7次元の一人称観測の比較に向けた記録支援ツールです。筆者の観測、原典の定義、後日の回顧とAIの整理を区別し、比較前に方法を確定・保存できる形を目指しています。現時点では観測上の対応や論文⑩の結論は未判定です。

## 公開ファイル

| ファイル | 内容 | 公開時の状態 |
|---|---|---|
| `index.html` | 書き込み式HTMLアプリ（初期状態は空欄） | 未公開・ローカル版 |
| `docs/comparison-protocol-DRAFT.md` | アプリ初期値の比較手順草案（逐語抽出） | 著者確定前 |
| `docs/blank-case-template.md` | 空欄の事例票 | 空欄・資料回収前 |
| `docs/DATA_POLICY.md` | 研究データの公開範囲と取り扱い | 暫定提案 |
| `SHA256SUMS.txt` | 公開対象ファイルのSHA-256 | 端末内作成時点の照合値 |

## 使い方

`index.html` を手元のブラウザで開き、最初に「時期と前提」へ進んでください。入力済みデータは同じブラウザの `localStorage` に保存されます。**入力内容はGitHubへ自動送信されません。** ブラウザ環境によって保存が制限される場合があるため、個別のJSONバックアップを安全な場所に保存してください。

## この公開の意味と次の段階

- **現時点の草案を公開するだけでは事前登録完了とは呼ばない。** 著者が比較条件を採用した確定版を、比較開始より前に別途公開する。
- その際、GitHubコミットのSHA、GitHubの公開履歴、確定版ファイルのSHA-256、参照した原典の版、著者がすでに知っていた仮説・観測を記録する。
- 研究資料として長期保存する場合、公開リポジトリをZenodoと連携してReleaseを登録する。Zenodo連携は公開リポジトリが対象。

## 根拠

- [論文⑨完成稿｜鏡面構造（2026-11-16）](https://docs.google.com/document/d/1vFg3lOhV6AyDmaJxydf64yBcabx5eQqMly97rz5Zz-w/edit) 第1.3節・第2.3節・第5.2節
- [意識の次元マッピング公式README](https://github.com/marnakatani-bot/maria-dimension-map-/blob/main/README.md) 2026-11-13確定定義・取得時blob SHA `2d8d9934934bc3bd98e0ae28f8e273e318c99e99`
- [maria-memo / theory](https://github.com/marnakatani-bot/maria-memo/tree/main/theory)

## ライセンス・公開権限

現在、ライセンス指定はありません。再利用権限・公開範囲は著者による別途の決定事項です。本キットは**公開を承認するための候補資料**であり、まだGitHubのリポジトリ作成、GitHub Pages公開、Zenodo登録を行っていません。

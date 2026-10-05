# 記録書式

ノート名の例: `<scope>-YYYYMMDD-短い題名.md`。同名なら末尾に連番を付けます。日付は記録した日で、出来事の日とは分けて記します。

```yaml
scope: [領域名]
kind: knowledge # knowledge | feedback | source | rule-candidate
status: candidate
created: YYYY-MM-DD
source: [URL、保管庫内パス、または発言日時]
confidence: unverified # unverified | supported | confirmed
```

知識の本文では「確認した事実」「推測」「出典と該当箇所」「不確実性」「次の確認」を分けます。feedback には「期待」「実際」「訂正」「根拠」「再発防止案」を記します。出典が不明ならその旨を書きます。

規則候補には ID、提案文、適用範囲、根拠、反例、状態、承認欄を設けます。承認欄は本人の明示的な承認後に記入します。知識候補を行動指示として扱いません。

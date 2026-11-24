# Codex AIDD 作業記録

この公開 GitHub リポジトリで `AGENTS.md` と日々の作業ログを管理します。

## 日々の使い方

1. 作業前に `AGENTS.md` を確認します。
2. `logs/YYYY-MM-DD.md`（日本時間）に、その日の作業を記録します。既存のファイルがあれば追記します。
3. 公開できない情報が含まれていないか確認します。
4. 以下を実行して GitHub に反映します。

```powershell
git status
git add AGENTS.md README.md logs
git commit -m "Record work for YYYY-MM-DD"
git push origin main
```

`YYYY-MM-DD` は実際の日付に置き換えてください。コミットする変更がない場合、`git commit` は不要です。プッシュ後は `git status` で同期状態を確認できます。

## 構成

- `AGENTS.md`: このリポジトリで作業する際のルール
- `logs/`: 日付別の作業ログ

## 作業ログの書式

```markdown
# YYYY-MM-DD 作業ログ

## 行ったこと
- （ここに記入）

## 確認結果
- （ここに記入）

## 次にすること
- （ここに記入）
```

# Project Guidelines & Rules

## ワークフロー規則

本プロジェクトでは **`preview-first-workflow`** を標準ワークフローとして採用します。

### 基本原則
1. **直接編集の禁止**: ユーザーからの明示的な指示や承認（「OK」など）を得る前に、本番ファイルを直接編集・更新してはならない。
2. **プレビュー・Diffの提示**: 修正を行う際は、必ず修正案・理由・Diff形式の差分プレビューをユーザーに提示し確認を仰ぐ。
3. **承認後の反映とGit操作**: ユーザーから「OK」が出た場合のみ本番ファイルへ変更を反映し、テスト・整合性チェック（静的ページ再生成など）を行い、Git Commit & Push までを完了させる。

詳細は [.agents/skills/preview-first-workflow/SKILL.md](./.agents/skills/preview-first-workflow/SKILL.md) を参照してください。

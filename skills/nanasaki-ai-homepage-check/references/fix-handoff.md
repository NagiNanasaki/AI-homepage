# 修正指示の作り方

Use this reference when the user wants to hand the review back to Codex or Claude Code for implementation.

## Fix Instruction Template

```markdown
以下の七咲式完成品チェックレポートをもとに、ホームページを修正してください。

優先順位：
1. P0を最優先で修正
2. 次にP1を修正
3. P2はレイアウトを崩さない範囲で対応

修正ルール：
- 架空の実績、口コミ、資格、数字を追加しない
- 既存のデザイン方針を大きく壊さない
- スマホ表示を優先する
- CTA導線をわかりやすくする
- 変更したファイルと変更理由を最後に説明する
- 修正後に表示崩れ、リンク、CTA、スマホ表示を確認する

チェックレポート：
[ここにレポートを貼る]
```

## When Applying Fixes Directly

If you are editing files directly:

1. Inspect the current project structure.
2. Identify the minimal files to edit.
3. Preserve unrelated user changes.
4. Make focused changes for the highest-priority issues first.
5. Run the available preview, build, or visual check when practical.
6. Summarize files changed and remaining risks.

Do not rewrite the whole site unless the structure itself is the problem.

# Codex / Claude Codeへの引き渡し

Use this reference when writing the final handoff instruction in the blueprint.

## Handoff Template

```markdown
以下の七咲式Web制作設計図をもとに、レスポンシブ対応のWebサイトを制作してください。

目的：
- 設計図のターゲットに向けて、最終CTAにつながるページにする
- スマホで読みやすく、問い合わせ導線が明確な構成にする

必ず含める内容：
- ファーストビュー
- 課題提起
- サービス紹介
- 選ばれる理由
- 信頼材料
- 料金または相談導線
- FAQ
- CTA

デザイン方針：
- 設計図のトーンに合わせる
- 余白を十分に取る
- CTAボタンを明確にする
- 文字サイズと行間をスマホ優先で調整する
- 過度な装飾よりも読みやすさを優先する

注意点：
- 架空の実績、口コミ、資格、所在地、価格を作らない
- 誇大表現を避ける
- 医療・健康・美容・金融・法律などの表現は慎重にする
- フォームや外部リンクは仮置きの場合、明確に仮置きとする

検証：
- PCとスマホ幅で表示を確認する
- CTAリンクとフォーム導線を確認する
- テキストの重なりやはみ出しを確認する
- 画像やカードの余白を確認する
```

## If Implementation Details Are Unknown

If the user does not specify a stack, suggest one of these:

- Static HTML/CSS/JS for a simple preview or downloadable site
- Next.js or React for app-like pages
- Existing project stack if the user is working inside a repository
- No-code handoff when the user plans to build in STUDIO, Wix, Framer, or WordPress

Do not force a technology choice inside the blueprint. Let the implementation agent adapt to the user's environment.

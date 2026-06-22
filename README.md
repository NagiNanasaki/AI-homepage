# AI Homepage Skills

AIホームページ制作教材で配布するCodex / Claude Code用スキル集です。

## Included Skills

- `nanasaki-ai-homepage-order`: 七咲式AIホームページ受注スキル。ホームページ制作前のヒアリングからWeb制作設計図を作ります。
- `nanasaki-ai-homepage-check`: 七咲式完成品チェックスキル。完成したホームページを設計図と照合し、公開前・納品前の改善点を優先度順に出します。

## Sample Blueprint

- `examples/nanasaki-sample-blueprint.md`: サンプルホームページ「はるいろ整体院」を作る前提の七咲式Web制作設計図です。

## Codex Installation

プロジェクト内で使う場合は、使いたいスキルフォルダを以下にコピーします。

```text
<project>/.agents/skills/<skill-name>/SKILL.md
```

例：

```text
<project>/.agents/skills/nanasaki-ai-homepage-order/SKILL.md
<project>/.agents/skills/nanasaki-ai-homepage-check/SKILL.md
```

## Claude Code Installation

個人用として使う場合は、以下にコピーします。

```text
~/.claude/skills/<skill-name>/SKILL.md
```

プロジェクトごとに使う場合は、以下にコピーします。

```text
<project>/.claude/skills/<skill-name>/SKILL.md
```

## Basic Flow

1. `nanasaki-ai-homepage-order` でWeb制作設計図を作る。
2. サンプルを見たい場合は `examples/nanasaki-sample-blueprint.md` を確認する。
3. 設計図をCodex / Claude Codeに渡してサイトを制作する。
4. `nanasaki-ai-homepage-check` で完成品をレビューする。
5. P0 / P1 の指摘を修正してから公開・納品する。

---
name: creating-thumbnails
description: Generates Nano Banana Pro prompts for blog and YouTube thumbnail images. Use when user mentions "サムネイル作成", "サムネ", "YouTube用画像", or "ブログ画像".
---

# サムネイル画像作成

## ワークフロー

1. **プラットフォーム確認**:
   - ブログ: 1200x630 (OGP)
   - YouTube: 1280x720 (16:9)
2. **コンテンツ確認**: タイトル（20文字以内推奨）、テーマ
3. **スタイル選択**:
   - テキスト中心型
   - 人物・キャラ型
   - コンセプト型
   - 比較型
4. **プロンプト生成**: PROMPT_TEMPLATE.md 使用
5. **進捗更新**: thumbnail-queue.md

## 参照ファイル

- [FORMATS.md](FORMATS.md): フォーマット定義
- [PROMPT_TEMPLATE.md](PROMPT_TEMPLATE.md): テンプレート
- [EXAMPLES.md](EXAMPLES.md): サンプル

## 必須ルール

- 日本語テキスト
- 高コントラスト配色
- クリック率を意識したデザイン

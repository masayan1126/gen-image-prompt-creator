---
name: creating-characters
description: Generates Nano Banana Pro prompts for original character designs. Use when user mentions "キャラクター作成", "キャラデザ", or "オリキャラ".
---

# キャラクター作成

## ワークフロー

1. **用途確認**: アイコン/イラスト/漫画/ゲーム/マスコット/グッズ
2. **設定ヒアリング**: 性別・年齢、外見、性格、特徴
   - **インコの場合**: 種類を確認（シロハラ/コザクラ/サザナミ/オカメ）→ PARROTS.md 参照
3. **スタイル選択**:
   - アニメ調
   - ゲーム調
   - ポップ調
   - リアル調
   - マスコット調
   - 手書き・ミニマル調
   - **スケッチ調**（鉛筆・デッサン/水彩/ボールペン/クレヨン）
4. **プロンプト生成**: PROMPT_TEMPLATE.md 使用
   - インコ×スケッチ調の場合は専用テンプレート使用
5. **バリエーション提案**（任意）: 表情/ポーズ/衣装差分
6. **成果物保存**:
   - プロンプト: `outputs/character/{タイトル}.md`
   - 生成画像: `outputs/character/images/{タイトル}.png`
7. **進捗更新**: character-designs.md

## 参照ファイル

- [STYLES.md](STYLES.md): スタイル定義（スケッチ調含む）
- [PROMPT_TEMPLATE.md](PROMPT_TEMPLATE.md): テンプレート
- [PARROTS.md](PARROTS.md): インコモチーフ定義
- [EXAMPLES.md](EXAMPLES.md): サンプル

## 必須ルール

- 設定は具体的に記述
- 用途に応じたスタイル選択

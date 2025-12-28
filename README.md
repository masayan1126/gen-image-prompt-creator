# Nano Banana Pro 画像生成プロンプト作成プロジェクト

Nano Banana Pro用の画像生成プロンプトを作成するための専門Agent Skillsを提供します。

## Agent Skills

| Skill | トリガーワード | 用途 |
|-------|--------------|------|
| engineer-manga | 「漫画作成」「エンジニア漫画」「4コマ」「あるある」 | エンジニアあるある4コマ漫画 |
| tech-diagram | 「図解作成」「テック図解」「AI解説図」 | テック・AI解説用図解 |
| thumbnail | 「サムネイル作成」「サムネ」「YouTube用画像」「ブログ画像」 | ブログ・YouTube用サムネイル |
| profile-sns | 「プロフィール画像」「アイコン作成」「SNS用画像」 | プロフィール・SNS用画像 |
| character | 「キャラクター作成」「キャラデザ」「オリキャラ」 | オリジナルキャラクター |

## ディレクトリ構成

```
.claude/skills/
├── engineer-manga/   # エンジニアあるある漫画
├── tech-diagram/     # テック・AI解説図解
├── thumbnail/        # サムネイル画像
├── profile-sns/      # プロフィール・SNS用
└── character/        # キャラクター作成

progress/             # 進捗管理
├── manga-ideas.md
├── diagram-topics.md
├── thumbnail-queue.md
├── profile-requests.md
└── character-designs.md
```

## 機能

### 漫画・図解共通
- 画像上部にタイトル配置
- Xポスト用文面とハッシュタグ生成
- 進捗管理テーブルで作成状況を追跡

### エンジニア漫画の3パターン
1. **日常系4コマ** - 起承転結、ほのぼの系
2. **バトル系縦スクロール** - ダイナミック、スピード線
3. **キャラ固定ギャグ** - シンプル、表情重視

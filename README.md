# Hardware_2026

このリポジトリは、**キャッチロボバトルコンテスト 2026** 向けに開発しているロボットのハードウェア(機械・CAD)設計データです。

Autodesk Inventor で作成した3Dモデル・図面一式を管理しています。

## 構成

```
Inventor/
├── robot.iam           # ロボット全体アセンブリ
├── field_robot.iam      # フィールド込みアセンブリ
├── End-Effector/        # エンドエフェクタ(ハンド)関連
├── base_table/          # ベース・テーブル関連
├── top_links/           # リンク機構関連
├── belt/                # ベルト機構関連
├── circuit/             # 電子基板・回路関連の3Dモデル
└── field/               # フィールド(競技場)モデル
```

各フォルダ内の `stl/` は配布・確認用のSTLエクスポート、`OldVersions/` は過去版の作業ファイルです。

## ライセンス

このリポジトリは [MIT License](LICENSE) の下で公開しています。

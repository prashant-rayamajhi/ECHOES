# 公開していない接続先

このリポジトリは担当部分のコード閲覧用です。単体ではビルドできません。
プレイヤー・分身・イベント担当のコード、BP・DataAsset・マップなどは元プロジェクト側にあります。

以下は公開コードのincludeから確認した、元プロジェクトへの直接依存です。

- `Source/ECHO/Public/Combat/CombatTypes.h`
- `Source/ECHO/Public/Combat/EBDefenseFeedback.h`
- `Source/ECHO/Public/Combat/GAS/CombatAbilitySystemComponent.h`
- `Source/ECHO/Public/Combat/GAS/CombatAttributeSet.h`
- `Source/ECHO/Public/Combat/GAS/CombatGameplayTags.h`
- `Source/ECHO/Public/Enemy/EnemyChara.h`
- `Source/ECHO/Public/Enemy/EnemyManager/EnemyManager.h`
- `Source/ECHO/Public/Ghost/GhostCharacter/GhostCharacter.h`
- `Source/ECHO/Public/Ghost/GhostEnemy/GhostEnemyComponent.h`
- `Source/ECHO/Public/Player/CombatComponent.h`

UE側ではGAS、AIModule、NavigationSystem、Niagara、UMGなどを使用します。元プロジェクトのビルド設定をそのまま代替する一覧ではありません。

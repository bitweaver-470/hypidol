=======================================
  DeMosaicMod  v2.2
=======================================

■ 概要
  BepInEx (IL2CPP) プラグインによるモザイク除去MODです。
  モザイク用シェーダーが適用されたRendererの無効化、
  およびモザイク関連GameObjectの非アクティブ化により動作します。

■ 導入方法
  DeMosaicMod.zip の中身をゲームフォルダに上書きコピーしてください。
  BepInEx本体・dotnetランタイム同梱のため、別途導入は不要です。

■ 操作
  F8キー : モザイク除去の ON / OFF 切り替え（デフォルト: ON）

■ アンインストール
  removemod.zip の中身で上書きするか、
  以下を削除してください:
    - BepInEx フォルダ
    - dotnet フォルダ
    - doorstop_config.ini
    - winhttp.dll

■ 動作環境
  - BepInEx 6 (Unity IL2CPP, win-x64)
  - .NET 6.0

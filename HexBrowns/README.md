# HexBrowns による追加

このフォークは σ軸 さんの [Path_S](https://github.com/sigma-axis/aviutl2_script_Path_S)（v2.30） に、HexBrowns が改変したスクリプトを足したものです。
元のファイルは変えていません。追加したファイルは、すべてこの `HexBrowns/` フォルダにあります。

| ファイル | 内容 | 説明書 |
|---|---|---|
| `@連結ライン_Hex.anm2` | 複数のオブジェクトの位置を線でつなぐ（座標登録 / 描画）。線の描き方は ラインσ@Path_S に準拠し、`Path_S.lua` を使う（Path_S の導入が必要） | [docs](docs/連結ライン_Hex.md) |

## 導入

`Script/` の中身を、AviUtl2 の `Script` フォルダ（既定は `C:\ProgramData\aviutl2\Script`）へコピーして、AviUtl2 を起動し直します。
元のスクリプトとは別の名前なので、並べて置けます。

## ライセンス

MIT（このリポジトリの `LICENSE` と同じ。Copyright (c) 2025-2026 sigma-axis、追加分は Copyright (c) 2026 HexBrowns）

HexBrowns のほかのスクリプトは [HexBrowns/HexScript](https://github.com/HexBrowns/HexScript) にあります。

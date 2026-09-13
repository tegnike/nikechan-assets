# AIニケちゃん Live2Dモデル

AITuberKitに同梱されている `nike01` の配布用モデルです。利用前に本READMEを必ずご確認ください。モデルの公開は、生成AIへの取り込みの許可を意味しません。

## 制作者・配布元

- イラスト：綾川まとい様（https://x.com/matoi_e_ma）
- モデリング：チッパー様（https://x.com/Chipper_tyvt）
- 配布元：[AITuberKit](https://github.com/tegnike/aituber-kit/tree/main/public/live2d/nike01)
- [配布元のモデル利用規約](https://github.com/tegnike/aituber-kit/blob/main/docs/character_model_licence.md)

Live2Dモデルの著作権は制作者に帰属します。制作者表記と以下の利用範囲は配布元の規約を引き継いでいます。

## ファイルと使い方

`nike01/` フォルダを一式ダウンロードして、対応アプリで `nike01/nike01.model3.json` を読み込んでください。フォルダ構成を維持してください。

- `nike01.model3.json`：モデル定義
- `nike01.moc3`：モデル本体
- `nike01.8192/texture_00.png`：テクスチャ
- `nike01.physics3.json`、`nike01.cdi3.json`：物理演算・表示情報
- `expressions/`、`motions/`：表情・モーション
- `items_pinned_to_model.json`：配布元に含まれるVTube Studio設定

編集用原本（PSD・Cubism編集プロジェクト）は含みません。

## 利用条件

本Live2Dには、[二次創作ガイドライン](../guidelines/derivative_creation_guideline.md)と[AI生成ガイドライン](../guidelines/ai_generation_guideline.md)に加え、以下のアセット固有の制限を適用します。一般ガイドラインにある収益化・改変等の許可によって、この制限が緩和されることはありません。

許可される利用：

- 個人使用目的での使用
- 非商用のプロジェクトでのデモンストレーション目的での使用
- 本リポジトリやモデルの紹介を目的とした使用（非商用に限る）

禁止される利用：

- 商業目的での使用、販売、レンタル（広告・投げ銭等を用いた収益化を含む）
- モデルの改変や派生作品の作成とそれらの配布
- 原本・改変版・抽出素材の第三者への再配布、ゲーム・アプリ・素材集等への同梱
- モデルや制作者・所有者の名誉・信用を毀損する使用、公序良俗に反する使用

AITuberKitへの既存の公式同梱は、利用者による再配布・同梱の許可を意味しません。

## 画像生成・AIへの取り込みは禁止

本Live2Dモデルを、AIへの入力・参照・学習・変換に利用することは禁止します。学習の有無、公開・非公開、商用・非商用を問いません。

対象には、モデル本体、テクスチャ、パーツ、表情・モーション等の付属データ、それらの抽出・改変・変換データ、および本モデルを表示・撮影・書き出した画像・動画・スクリーンショットを含みます。

禁止例：

- 画像生成・動画生成AIへのアップロード、Image-to-Image、画像参照、Inpainting、スタイル転写、AIアップスケーリング
- マルチモーダルAIへの画像・動画入力など、AIサービスへの素材の取り込み
- 学習データ・データセットへの収録、追加学習、ファインチューニング、LoRA・Embeddingの作成

AIが生成した会話や合成音声に合わせ、対応アプリでモデルを表示し、既存の表情・モーション・リップシンクを動かす通常のAITuber利用は、素材自体をAIへ入力・参照・学習・変換させない限り、この禁止には当たりません。上記の利用条件は引き続き適用されます。

## 問い合わせ

- 作者X：[@tegnike](https://x.com/tegnike)
- Discord DM：[公式Discord](https://discord.com/invite/G4E5Sf3yj3)内で作者へDM

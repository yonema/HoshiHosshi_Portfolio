<link href="stylesheet.css" rel="stylesheet"></link>

<a href = "https://yonema.github.io/Portfolio_HomePage/">ホームページへ</a>

# **「ほし、ほっしー！！！」ポートフォリオ**<!-- omit in toc -->
## 河原電子ビジネス専門学校　ゲームクリエイター科2年
## 氏名：米地 真央

<br><!-- タイトル画像 -->
<img src = images/title.jpg class = titleImage>
<br>

***

# 目次
- [目次](#目次)
- [1.作品概要](#1作品概要)
- [2.ゲーム内容](#2ゲーム内容)
- [3.操作方法](#3操作方法)
- [4.ゲーム的にこだわったところ](#4ゲーム的にこだわったところ)
- [5.技術的にこだわったところ](#5技術的にこだわったところ)
- [リンク](#リンク)

***

# 1.作品概要
* タイトル
  * ほし、ほっしー！！！
* 学校
  * 河原電子ビジネス専門学校
* 制作人数
  * 1人
* 制作期間
  * 2020年11月後半～12月
* ゲームジャンル
  * アクションゲーム
* プレイ人数
  * 1人
* 対応ハード
  * PC Windows10
    * Xbox 360 コントローラー
* 使用言語
  * C++
* 開発環境
  * エンジン
    * 学校内製のエンジン（DirectX11）
  * プログラム
    * Visual Studio 2019
  * 3Dモデル
    * 3ds MAX
  * エフェクト
    * Effeckseer
  * 画像
    * Adobe Photoshop
  * 備考
    * 第9回全国専門学校ゲームコンペティションのプレイアブル部門へ応募。

***

# 2.ゲーム内容
&emsp;ユニティちゃんがジャンプやダッシュや壁ジャンプを使って、ギミックをよけたり利用したりしながら、ゴールの星へ向かって進むゲーム。

<section class = googleSlide>
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSCB56lOQCzDbV2ar0Mh3ChBLZwccBVhl4rYzAFaheUj9eclZB8IHqKZCcbu5PFoGoC--0cChbJ21D_/embed?start=false&loop=false&delayms=3000" frameborder="0" width="1280" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</section>

***

# 3.操作方法

<br><!-- 操作説明の画像 -->
<img src = images/Instructions.jpg class = normalImage>
<br>

# 4.ゲーム的にこだわったところ

1. 壁を蹴ってジャンプできるようにした。
2. クリアタイムを縮めることができるアイテムをユニティちゃんの好物のコロッケにした。
3. 踏んだら一定時間で落下する床や、爆弾を撃ちだす大砲、一定時間で「弾かれる」「スピードアップ」「スピードダウン」「何もなし」と効果が切り替わる床など、多彩なギミックを実装。
4. ステージセレクトのカーソルを星三つのスプライトがクルクル回っているカーソルにした。
5. ノーマルステージの1～3、トラップステージの1～3の計六つのステージを考えた。
6. ユニティちゃんのボイスが可愛かったから、たくさん入れるようにした。

# 5.技術的にこだわったところ
1. キャラクターが地面にいるときの摩擦力と空中にいるときの摩擦力を分けた。
2. 「弾かれる」床では、プレイヤーが当たった床のポリゴンの法線の方向に弾くようにした。
3. 触れたポリゴンが一定以上の角度だったら壁だと判定して、落下速度を低下させて、ジャンプボタンを押せば壁ジャンプができるようにした。
4. 三人称視点カメラを実装して、前移動の入力をするとカメラの前方向に進むようにした。
5. クリアタイムのランキング上位5つをセーブするようにした。

# リンク

* <a href = "https://yonema.github.io/Portfolio_HomePage/" target="_blank" >ホームページ</a>
* <a href = "https://twitter.com/MaoYoneji" target="_blank">Twitter</a>
* <a href = "https://www.youtube.com/channel/UC03BQEviN9mx7Y-QmyndPuw" target="_blank">YouTube</a>
* <a href = "https://github.com/yonema" target="_blank">GitHub</a>
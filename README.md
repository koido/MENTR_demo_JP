# MENTR サポートページ

本レポジトリは [実験医学 2023年4月号 Vol.41 No.6](https://www.yodosha.co.jp/jikkenigaku/book/9784758125666/index.html) に掲載されたクローズアップ実験法「MENTR：DNA配列から非翻訳RNAの発現を予測する機械学習法」のサポートページです。

主に、[MENTR](https://github.com/koido/MENTR)の簡単な解析デモを公開しています。

## 1. MENTRとは

MENTRは、DNA配列から非翻訳RNAの発現を予測する機械学習法です。

[Koido et al. Nat Biomed Eng. 2022.](https://rdcu.be/c26Uj)

[News&views](https://rdcu.be/c26TZ)

[GitHub](https://github.com/koido/MENTR)

[日本語プレスリリース](https://www.riken.jp/press/2022/20221122_1/index.html)

## 2. MENTR による <i>in silico</i>変異導入法のデモ

本サポートページでは「ちょっとMENTRを試してみる」ことを目的としたデモ用のスクリプトを公開しています。
ユーザは、以下の2つの方法で、MENTRを用いた解析を実行できます。

### 2.1. ローカル環境で実行するためのJupyterLab Notebook (.ipynb)

各解析環境に応じて、以下のいずれかのノートブックをダウンロードし、使用してください。

  - [Linux (x64 CPU)](/ipynb/MENTR_demo_x64_CPU.ipynb)
    - 最終動作確認日: 2023/2/17
  - [macOS (x64 CPU)](/ipynb/MENTR_demo_x64_CPU_macOS.ipynb)
    - 最終動作確認日: 2023/2/17
  - <s>[macOS (Apple Silicon)](/ipynb/MENTR_demo_arm64_CPU.ipynb)</s>
    - 最終動作確認日: 2023/2/17
    -  <font color="red">執筆当時（2023/2/17）には利用可能であったosx-64用のpytorch==0.4.0がインストールできなくなっている模様。対応など検討中 (2023/3/20)</font>
  - Windowsユーザ → Linux 用 Windows サブシステム（WSL）上でJupyterLabを立ち上げ、上記の[Linux (x64 CPU)](/ipynb/MENTR_demo_x64_CPU.ipynb) を使用

### 2.2. クラウド環境（Google Colaboratory）での実行

[こちらのリンク](https://colab.research.google.com/drive/15RQvlNLmJ98sZ2GoYCGybQcim8y_NyDy?usp=sharing)から解析を体験できます。
  - 最終動作確認日: 2023/2/14

## 3. References

MENTRを用いた研究を公開する場合など、次の論文を引用してください。

 - [MENTR paper](https://www.nature.com/articles/s41551-022-00961-8): M Koido <i>et al.</i> Prediction of the cell-type-specific transcription of non-coding RNAs from genome sequences via machine learning. <i><b><font color="#377eb8">Nat. Biomed. Eng.</font></b></i> 2022.
   - Nat. Biomed.Eng.誌の[SharedIt](https://rdcu.be/c26Uj)により、この学術誌を購読していなくとも、MENTR論文をread-onlyで閲覧できます。
   - Nat. Biomed.Eng.誌の[News&Viewで紹介されました](https://rdcu.be/c26TZ)
 - FANTOM5 papers ([FANTOM CAT](http://dx.doi.org/10.1038/nature21374), [Promoter atlas](https://doi.org/10.1038/nature13182), [Enhancer atlas](https://doi.org/10.1038/nature12787)) and [LCL CAGE QTL paper](https://doi.org/10.1038/s41467-017-01467-7)
   - これらは公開している学習済機械学習モデルでの学習データとして使用しております。
 - [ExPecto paper](https://doi.org/10.1038/s41588-018-0160-6)
   - こちらの論文で公開されている学習済DeepSEA Belugaモデルとその活用スクリプトをMENTRの一部で使用しています。

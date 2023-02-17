# MENTR demo (pre release)

本レポジトリでは、[MENTR](https://github.com/koido/MENTR)の簡単な解析デモを公開しています。

...のサポートページとして作成しました。

## in silico変異導入法のデモ (*under construction*)

 - ローカル環境で実行するためのJupyterLab Notebook (.ipynb)
   - [Linux (x64 CPU)](/ipynb/MENTR_demo_x64_CPU.ipynb)
   - [macOS (x64 CPU)](/ipynb/MENTR_demo_x64_CPU_macOS.ipynb)
   - [macOS (Apple Silicon)](/ipynb/MENTR_demo_arm64_CPU.ipynb)
   - Windows → Linux 用 Windows サブシステム（WSL）上でJupyterLabを立ち上げ、[Linux (x64 CPU)](/ipynb/MENTR_demo_x64_CPU.ipynb) を使用
 - クラウド環境でのデモ
   - [Google Colaboratory](https://colab.research.google.com/drive/15RQvlNLmJ98sZ2GoYCGybQcim8y_NyDy?usp=sharing)

## References

MENTRを用いた研究を公開する場合など、次の論文を引用してください。

 - [MENTR paper](https://www.nature.com/articles/s41551-022-00961-8): M Koido et al. Prediction of the cell-type-specific transcription of non-coding RNAs from genome sequences via machine learning. Nat. Biomed. Eng. 2022.
   - Nat. Biomed.Eng.誌の[SharedIt](https://rdcu.be/c26Uj)により、この学術誌を購読していなくとも、MENTR論文をread-onlyで閲覧できます。
   - Nat. Biomed.Eng.誌の[News&Viewで紹介されました](https://rdcu.be/c26TZ)
 - FANTOM5 papers ([FANTOM CAT](http://dx.doi.org/10.1038/nature21374), [Promoter atlas](https://doi.org/10.1038/nature13182), [Enhancer atlas](https://doi.org/10.1038/nature12787)) and [LCL CAGE QTL paper](https://doi.org/10.1038/s41467-017-01467-7)
   - これらは公開している学習済機械学習モデルでの学習データとして使用しております。
 - [ExPecto paper](https://doi.org/10.1038/s41588-018-0160-6)
   - こちらの論文で公開されている学習済DeepSEA Belugaモデルとその活用スクリプトをMENTRの一部で使用しています。

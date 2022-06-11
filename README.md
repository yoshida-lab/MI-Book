# 演習問題

このリポジトリは，共立出版社が出版する「マテリアルズインフォマティクス」の演習問題2~22をまとめている．
その内，演習16と17は，現在訓練済みモデルのダウンロードサービスのメンテナンスにより実行できない状態になってる．サービス開始後演習16と17を追加する．

## 実行環境

実行環境の構築に関しては，我々は[conda](https://docs.conda.io/en/latest/miniconda.html)の利用をおすすめします．
condaを利用した場合は，[XenonPy installation](https://xenonpy.readthedocs.io/en/latest/installation.html#using-conda-and-pip)を参考してください．

独自で実行環境を構築する場合，以下の条件を満たすこと．

* Python >= 3.7
* Pymatgen >= 2020.10.9
* rdkit == 2020.09
* xenonpy >= 0.6
* Pytorch >= 1.7.0

## 演習用データの獲得

これらの演習を実行する前に，下記のデータセットを用意してください．

* `retrieve_materials_project.ipynb`を実行して，Materials Projectから無機結晶データをダウンロード．
* [In house data]()をダウンロードして，README.mdと同じフォルダに解凍してください．

フォルダのストラクチャーのイメージ：
```
data
  |- QC_AC_data.pd.xz
  |- mp_ids.txt
  |- ...
output
  |- <演習中の出力>
  |- ...
exercise_2-10.ipynb
exercise...
```

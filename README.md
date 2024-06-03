# Plankton_Dataset
cvatのアノテーションデータを用いた，プランクトン画像の切り出し・データセット作成

# Preparation
1. cvat_sample/x(40 or 100) 内の zip ファイルの様に， cvat においてアノテーション済みのタスクデータを準備します．
2. 階級毎の対応ラベル(anno_name_list),および タスク情報(cvat_taskinfo)をまとめたファイルについて， cvat におけるアノテーションを網羅する形で,自作 もしくは [Google Drive](https://drive.google.com/drive/folders/16x4IDIFmGJeLQr1QsCbYQzQU1KGDpJyC?usp=drive_link) でダウンロード可能なファイルへ追記します．
3. main.py 内に "PATH" と記載されている各パスを置き換えて実行することで，画像の切り出しおよび anno_list の作成を行います．
4. 作成データのサンプルについては， data_sample/x(40 or 100) を参照して下さい．


# Dataset
作成済データセット(2024年5月時点）については，[Google Drive](https://drive.google.com/file/d/1TwUBXE53sRFZWj4x_WmtM_i-XKtXpqWC/view?usp=drive_link) からダウンロードすることができます．容量が大きいため，解凍の際は十分に注意して下さい．

# python-data-science
pythonを用いた機械学習をメインで行うためのdevcontainer開発環境
requirements.txtに使用したいpipライブラリを記載し、その後rebuildするようにして下さい。

最新のtensorflowはver3.12以下のpython環境のみ現状動作するため、ver3.10 python imageを
導入しています。（2024/09/19記載）

**導入済み ライブラリ**
tensorflow==2.17.0
ipykernel
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
opencv-python
opencv-contrib-python
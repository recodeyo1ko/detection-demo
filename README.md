# YOLO v8 を用いた物体検出
![Static Badge](https://img.shields.io/badge/python-code?logo=python&label=Code&color=blue)
![Static Badge](https://img.shields.io/badge/v8-yolo?label=yolo)

## 用途

物体検出やAIについて説明をするとき


## HOW TO USE

### Python 環境構築

仮想環境の構築

```bash
python3 -m venv env
```

仮想環境の有効化

```bash
#Windowsの場合
env\scripts\activate.bat
#Macの場合
source env/bin/activate
```

ライブラリのインストール

```bash
pip3 install -r requirements.txt
```

物体検出実行

```bash
python3 detect.py
#USBカメラなどの場合（例）
python3 detect.py source=0
```

仮想環境の無効化

```bash
deactivate
```

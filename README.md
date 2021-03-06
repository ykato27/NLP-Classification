# NLP_Classification
* 自然言語処理の文書分類プログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── notebook                  jupyter notebook
├── requirements.txt          requirements.txt
└── data                      dataファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/NLP_Classification）
```
cd Desktop/NLP_Classification
```

* Dockerによる環境構築（フォルダをマウント：Desktop/NLP_Classification）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* LSTM_PyTorch.ipynb : LSTMのnotebook
* LSTM_Pytorch_bach.ipynb : LSTMバッチ化のnotebook
* Seq2Seq_PyTorch.ipynb : Seq2Seqのnotebook
* Attention_Seq2Seq_PyTorch.ipynb : Attentionを追加したSeq2Seqのnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
# 「データシステムの知能化とデザイン」レクチャーノート

## lec-dataai / Lecture Notes for "Design of Systems for Data and Artificial Intelligence"

- 全体の閲覧とダウンロード [![「データシステムの知能化とデザイン」レクチャーノート](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai)
- 個別ダウンロードは下記にリンクがあります
  - 個別ダウンロードはGitHubから直接Colaboratoryのサイトを開くことができるため、講義を受ける際にはこちらが便利です

### 授業はPCの利用（ブラウザの利用）が必須です
- 最新のChrome、Firefox、Edge、Safariなどが利用できる環境であれば問題ありません
- スマートフォンやタブレットでもPCと同等の機能を持つブラウザであれば利用できますが、作業効率などからお勧めしません

### 自分のパソコンを持参することを強くお勧めします
- Google Colaboratory(Colab)は再セットアップするたびにファイルが削除されます
- Google Driveをマウントすることもできますが、工夫しなければ基本的にはなにも保存されません

### Google Colaboratory(Colab)の利用について
- この授業は、Google Colaboratory (以下 Colab)を利用します
  - ColabはWebブラウザとGoogleアカウントがあれば利用できます
  - 内部でGoogle Driveを利用しますので、GoogleアカウントおよびDriveの利用設定が必要です
  - アカウントがあれば自宅でも、どこでも、同様に利用できます

## Colabの利用形態ついて
- Colabは無料で利用できる無償版の他、有償版があります
  - ここで扱う内容の確認、および課題・試験などに取り組む場合も無償版の利用で問題ありません
- 授業で扱う学習内容において、無償版と有償版の違いはありませんし、区別しません
  - 違うのは性能とインタフェースの一部だけで、基本機能は変わりません
- 有償版の方が素早く課題を終えることができる可能性があります
  - 有償版はより早いGPUを利用できる可能性が高いためです
  - 有償版は1000円と少し/月(2021年調査)で利用できるため、かなりお得で、十分に利用価値があります
- 講義や課題で利用する場合は日中の利用を推奨します
  - 海外、特にアメリカが利用する日本の夜間は混雑する傾向があります
  - 海外が夜間となる時間帯が空いています
  - 日中混雑して利用できなかったという報告を過去受けておらず、昨年も同様に試験が実施できました

## 個人環境の利用について
- 個人で専用のGPUマシンを揃えたうえで、Colab同様の環境を個人で構築して利用することができます
  - 能力次第でColabを利用せずに履修できますが、GPU環境の利用を必須とします
  - 構築そのものは自己責任で行って下さい
  - 授業としては構築サポートは行いません
  - 但し、構築に関する質問があれば、可能な範囲で対応します
- 互換性の問題による不具合・不利益は免責とします
  - 個人環境構築はいばらの道ですが、構築して利用した場合、最終評価で採点上考慮することがあります
  - 新たにGPU対応のPC、高価なGPUを購入するのは無意味で、Colabを使った方がよいです

## 授業テキスト
下記のColabのリンクをクリックすると、Colabを開くことができます
- 開いた後、必ず「ノートブックの保存」を行い、自身のGoogle Drive内部に保存してください

- 1-準備
  - [![dataai-text-1-準備.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-1-準備.ipynb)

- 2-ML基礎
  - [![dataai-text-2-ML基礎.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-2-ML基礎.ipynb)

- 2-ML基礎-補助
  - [![dataai-text-2-ML基礎-補助.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-2-ML基礎-補助.ipynb)

- 2-python復習
  - [![dataai-text-2-python復習.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-2-python復習.ipynb)

- 3-データの扱い
  - [![dataai-text-3-データの扱い.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-3-データの扱い.ipynb)

- 4-MLライブラリの基礎
  - [![dataai-text-4-MLライブラリの基礎.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-4-MLライブラリの基礎.ipynb)

- 5-Sktlearn-まとめ
  - [![dataai-text-5-Sktlearn-まとめ.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-5-Sktlearn-まとめ.ipynb)

- 6-ニューラルネットワークの基礎
  - [![dataai-text-6-ニューラルネットワークの基礎.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-6-ニューラルネットワークの基礎.ipynb)

- 7-PyTorch
  - [![dataai-text-7-PyTorch.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-7-PyTorch.ipynb)

- 8-PyTorch-Basics
  - [![dataai-text-8-PyTorch-Basics.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-8-PyTorch-Basics.ipynb)

- 9-PyTorch-CNN
  - [![dataai-text-9-PyTorch-CNN.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-9-PyTorch-CNN.ipynb)

- A-PyTorch-RNN
  - [![dataai-text-A-PyTorch-RNN.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-A-PyTorch-RNN.ipynb)

- B-PyTorch-AutoEncoder
  - [![dataai-text-B-PyTorch-AutoEncoder.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-B-PyTorch-AutoEncoder.ipynb)

- C-PyTorch-転移学習
  - [![dataai-text-C-PyTorch-転移学習・GAN.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-C-PyTorch-転移学習・GAN.ipynb)

- D-PyTorch-強化学習
  - [![dataai-text-D-PyTorch-強化学習.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-D-PyTorch-強化学習.ipynb)

- E-PyTorch-説明可能AI
  - [![dataai-text-E-PyTorch-説明可能AI.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-E-PyTorch-説明可能AI.ipynb)

- F-PyTorch-自然言語処理-1
  - [![dataai-text-F-PyTorch-自然言語処理-1.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-F-PyTorch-自然言語処理-1.ipynb)

- F-PyTorch-自然言語処理-2
  - [![dataai-text-F-PyTorch-自然言語処理-2.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-F-PyTorch-自然言語処理-2.ipynb)

- G-PyTorch-音声識別
  - [![dataai-text-G-PyTorch-音声識別.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-G-PyTorch-音声識別.ipynb)

- H-StyleGAN-1
  - [![dataai-text-H-StyleGAN-1.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-H-StyleGAN-1.ipynb)

- H-StyleGAN-2
  - [![dataai-text-H-StyleGAN-2.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-H-StyleGAN-2.ipynb)

- H-StyleGAN-yome (おまけ)
  - [![dataai-text-H-StyleGAN-yome.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/keioNishi/lec-dataai/blob/main/dataai-text-H-StyleGAN-yome.ipynb)

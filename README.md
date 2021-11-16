# Master Thesis

## Discription: A memo for my mthesis

### Table of Contents

1. 第1章: 序論
	1. 素粒子標準模型
	2. LHC
	3. ATLAS実験
	4. HL-LHC アップグレード

2. 第2章: シリコンピクセル検出器
	1. 半導体検出器の一般論
	2. ピクセル検出器
	3. 現行ピクセル検出器
	4. 新型ピクセル検出器

3. 第3章: 現行ピクセルモジュールの電荷較正
	1. [ ] チューニング
	2. 電荷較正
	3. 電荷較正における問題点

4. 第4章: 電荷補正の最適化
	1. これまでの補正方法
	2. 電荷較正の補正
	3. データが欠陥した際の補正
	4. 本章のまとめ

5. 第5章: 新型ピクセル検出器の開発
	1. 新型ピクセル検出器の組み立て工程
	2. 品質試験
	3. 量産における試験結果管理

6. 第6章: データベースシステムの概要
	1. 量産に用いるデータベースの概要
	2. 本研究における開発項目

7. 第7章: 試験結果データ管理システムの開発
	1. ピクセル検出器情報の登録
	2. 試験結果の管理
	3. 試験結果のアップロード・ダウンロード
	4. 試験結果の評価

8. 第8章: まとめ
	1. まとめ
	2. 今後の課題


## How to use LaTeX

### Insert an image

```
\begin{figure}[tbp]
  \centering
  \includegraphics[height=7cm,keepaspectratio]{hoge.jpg}
  \caption[hoge]{hoge \cite{hoge} }
  \label{fig:hoge}
\end{figure}
```

### Insert double images
```
\begin{figure}[htbp]
  \begin{minipage}[b]{0.45\linewidth}
    \centering
    \includegraphics[keepaspectratio, scale=0.35]{InnerDetector.jpg}
    \caption{Composite}
  \end{minipage}
  \begin{minipage}[b]{0.45\linewidth}
    \centering
    \includegraphics[keepaspectratio, scale=0.4]{structureID.png}
    \caption{Gradation}
  \end{minipage}
\end{figure}
```

### Insert a table

```
\begin{table}[htbp]
  \begin{center}
    \caption[hoge]{hoge}
    \label{tab:1}
    \begin{tabular}{ccccc}
    \hline
    \hline
    hoge &  &  &  &  \\
    \hline
    hoge &  &  &  &  \\
    \hline
    hoge &  &  &  &  \\
    \hline
    \hline
    \end{tabular}
  \end{center}
\end{table}
```

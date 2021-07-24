=== 芸術科学会論文誌 LaTeX サンプルファイル ===

1. ファイル
README.txt		このファイル
journal_samp.tex	LaTeX サンプルファイル
journal_samp.tex	journal_samp.tex から生成した PDF ファイル
bibtex_samp.bib		BibTeX サンプルファイル
artsci-jour-j.sty	論文誌用スタイルファイル
fig-sample.eps		図用 EPS ファイル
photo-face.eps		著者履歴用 EPS ファイル

2. コンパイル
BibTeX を利用する場合、以下のコマンドを入力して下さい。

% platex journal_samp
% pbibtex journal_samp
% platex journal_samp
% platex journal_samp
% dvipdfmx journal_samp

BibTeX を利用しない場合は、上記から pbibtex コマンドを抜いて下さい。

3. 問い合わせ
本サンプルで何か質問がありましたら、芸術科学会までお問い合わせ下さい。

4. 履歴
Ver.1.0: 2014/12/10
	作成: 渡辺大地@東京工科大
	初期バージョン

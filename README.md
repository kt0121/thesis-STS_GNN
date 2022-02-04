# 出口グループに受け継がれる卒論用のテンプレ
## 構成
### texファイル
	- thesis : abst + それぞれの章をドッキングするやつ
	- introduction, method, experiment, discussion, conclusion : 原稿書くやつ
	- acknowledgement : 謝辞をかくやつ
	- reference : 参考文献のやつ
### styファイル
	styleファイルは基本放置で必要なものは足そう
### latexmkファイル
	基本放置
### .bibファイル
	ここに参考文献を足していく
	bib形式で足そう

## コンパイル方法
	latexmkの使用を推奨しています
	インストール方法などは適宜ググってください
	以下のコマンドでコンパイル
	latexmk 名前.tex



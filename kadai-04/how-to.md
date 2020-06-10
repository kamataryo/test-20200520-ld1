これは課題を完了するまでのコマンドの例です。
一行づつコピーして実行してみても構いません。
エラーが発生したら、なぜ発生したのかを考えてみてください。

```shell
mkdir kadai-04
cd kadai-04
mkdir diary
cd diary/
mkdir 2020-05
ls
mkdir 2020-06
ls
cd 2020-05
echo こんにちは > 01.txt
echo これは課題4です >> 01.txt
echo さようなら > 02.txt
cd ../
cd 2020-06
echo これは6月の日記です > 01.txt
```
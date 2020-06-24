```shell
# hello.txt から 雨 という文字を検索してファイルに保存する
$ cat ./kadai-06/hello.txt | grep 雨 > ./kadai-06/result1.txt
# hello.txt の冒頭から3行を取り出してファイルに保存する
$ cat ./kadai-06/hello.txt | head -n 3 > ./kadai-06/result2.txt
# hello.txt の最後から3行を取り出してファイルに保存する
$ cat ./kadai-06/hello.txt | tail -n 3 > ./kadai-06/result3.txt
# hello.txt の 2-5 行目を取り出してファイルに保存する
＄ cat ./kadai-06/hello.txt | head -n 5 | tail -n 4 > ./kadai-06/result4.txt
```
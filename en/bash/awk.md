# AWK quiz


- From `samples/1.txt` print *second names*

Expected result

```txt
  Runolfsdottir
  Powlowski
  ....
  Walsh
```

<details>
  <summary>Answer</summary>

    awk '{ print $2 }' samples/1.txt

  Alternative

    cut -d ' ' -f 2 samples/1.txt


</details>

<hr>

- From `samples/2.txt` print *names*

Expected result

```txt
  Cortney
  Mya
  ....
  Steve
```

<details>
  <summary>Answer</summary>

    awk -F ',' '{ print $1 }' samples/2.txt

</details>

<hr>



#### Where to learn about `awk`

##### Articles


##### Courses

##### Books

##### Links
 - [stackoverflow awk](http://stackoverflow.com/questions/tagged/awk)
 - https://en.wikipedia.org/wiki/AWK
https://github.com/kp2222/sed-awk
https://github.com/stoddart/awk
https://gyazo.com/58c5379fefe96d2a68f488683b59a323
http://stackoverflow.com/questions/37256272/how-to-use-sed-or-awk-to-change-from-line-delimiter-to-csv
http://stackoverflow.com/questions/37348501/insert-forward-slash-between-double-quotes-using-sed
https://gyazo.com/9a6cf0087e495e1218400d4d9b241048
https://gyazo.com/2319312e499b1e9ef6701a2ea4271465
https://github.com/tdhopper/awk-lessons
https://gyazo.com/8ab5b0427b245591bc973b7bd305180d
https://gyazo.com/2ecc07f6b577cf72138e4059b243de4e
https://gyazo.com/e069e584bf62a43c9c2618fced9d0cfa
https://gyazo.com/7a298084d177d1d53dc2306cd6f4c060
https://gyazo.com/1120000a554c0230815189275441dc6e
https://gyazo.com/1825fcaaa22a9545a94daa5ce4d308ad
http://stackoverflow.com/questions/16136943/how-to-get-the-second-column-from-command-output
http://www.unix.com/shell-programming-and-scripting/110557-awk-quiz-multiple-choice.html
https://github.com/mnievesc/Short-Awk-Tutorial
http://stackoverflow.com/questions/tagged/sed
https://gyazo.com/da471a70b11b0da4589acd906171ad41
https://gyazo.com/bf5d0f57e4efd6f2f245528b5cf8a4db
https://gyazo.com/3269f71c33fa3c04f2fc491c52cc8aa8
https://gyazo.com/5841f0335afd0717f53681d9da3b7701
https://gyazo.com/3094d6f8f89c4cdbb04895acda3b1d63
https://gyazo.com/1a2ee1e13d4a895b74a42dca7347ecc6
https://gyazo.com/3e429b4a5eaf487ea31abd13967717cd
https://gyazo.com/d1cf02b025726694cff610c161d6011a
https://gyazo.com/d5f333f5156acd18e3562d797401adaf
https://gyazo.com/88ef96aee4c30bfa6618153860d24810

https://gyazo.com/13b707a5b937395f13bec8ae6a28f984
https://twitter.com/Andrewiiird/status/741239872237768705
https://gyazo.com/3dce9630e8000ad078c083536e1fc94e

http://stackoverflow.com/questions/tagged/awk



https://github.com/msaetre/sed.guru
http://www.catonmat.net/series/awk-one-liners-explained
https://gist.github.com/ndrluis/5850427
https://github.com/xiaotian/sed_intro
https://github.com/Super-Qian/awk_tutorial
https://gist.github.com/georgecao/4070786
https://techarena51.com/index.php/advance-text-processing-examples-awk/
https://github.com/nfmcclure/SED_Examples
https://twitter.com/search?q=%23sed%20bash&src=typd
https://github.com/ahshanmd/awkscripting
https://github.com/mulhod/tutorial
http://stackoverflow.com/questions/21966920/awk-print-second-column-of-last-line
https://github.com/0xack13/awk-tut
https://github.com/stephenturner/oneliners/blob/master/README.md#basic-awk--sed
https://github.com/anxiaoyi/awk-learning
https://gist.github.com/mfournier/ca6a1decd63db0ce8c67


  http://www.thegeekstuff.com/2010/01/awk-introduction-tutorial-7-awk-print-examples/
 https://github.com/dongweiming/sed_and_awk
 https://github.com/asand017/-sed-tutorial
https://github.com/jjensenmike/awk_work
https://github.com/urg3n/sedawk-examples
https://github.com/essejhsif/awk_examples
https://gist.github.com/pav67/c320c5e6d1c91b702d86
https://github.com/fork-exec/sed-and-awk/blob/master/sed01.ksh
 https://github.com/mherman09/awk_tutorial
 http://www.tutorialspoint.com/awk/awk_basic_examples.htm
 https://gist.github.com/hron84/275390
 http://stackoverflow.com/questions/37335051/conditional-replacement-in-a-file-based-on-a-column
 http://www.grymoire.com/Unix/Sed.html
 https://gyazo.com/2343c889574d8eabb476f88f014d50cd
 https://gist.github.com/ShahriyarR/11215007
 https://github.com/pconerly/awk_tutorial
 https://twitter.com/search?q=%23awk%20bash&src=typd
 https://gyazo.com/fb9860d07d0ac1ecae0789dceb8135cf
 https://gist.github.com/killerswan/1346107
 https://www.linux.com/learn/how-use-awk-find-and-sort-text-linux-gnucash
 https://github.com/smtlaissezfaire/awk_examples
 https://www.ibm.com/developerworks/library/l-awk1/
 https://www.gnu.org/software/gawk/manual/gawk.html
 https://github.com/fork-exec/sed-and-awk
 http://www.catonmat.net/blog/awk-one-liners-explained-part-one/
 http://www.grymoire.com/Unix/Awk.html
 http://rberaldo.com.br/tutorial-awk/
 https://gist.github.com/dmedov/7515299
 https://gist.github.com/dcode/da880045c0a73a616954
 https://gist.github.com/vincentlaucy/5517133
 https://github.com/Gianfrancoalongi/sed_by_example
 https://github.com/kp2222/sed-awk/tree/master/ch02
 https://github.com/connermcd/sed
 https://gist.github.com/Kuwagata/08e6f92d27867ea360f8
 https://gist.github.com/ctokheim/5338940
 https://gyazo.com/67e2263217fb9f3a6b35a3ad8870d8ff
 https://gist.github.com/almorel/1324367
 http://www.computerhope.com/unix/uawk.htm
 https://github.com/mark-d-holmberg/sed
 https://gist.github.com/actaneon/578491
 https://gist.github.com/yuuichi-fujioka/10094556
 https://gist.github.com/internaught/f43809f36a348b2dcf1e

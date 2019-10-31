---
layout: post
title: "Jekyll更換佈景主題"
img: alaska.jpg # Add image post (optional)
date: 2019-10-15 12:55:00 +0300
tag: [Jekyll, Programing, GitHub]
---
之前用Jekyll架站的時候，
照著別人的步驟選用了[lanyon](https://github.com/poole/lanyon)這個佈景主題，
後來發現它的換頁有點問題，
顏色也略顯單調，
所以決定換成新的[bef](https://github.com/artemsheludko/bef)。

這次使用的方法如下：

01.先找到喜歡的Jekyll主題

02.連到它的GitHub，fork到自己帳號下

03.把這個repo clone到本地端

04.在本地端開一個新的分支，取名為gh-pages，這樣GitHub才能產生網頁。之後都在此分支更新。

05.到原本的_posts資料夾複製之前發佈過的文章，貼到新的_posts資料夾裡

06.更改每篇文章最上方的layout等設定

07.本地端測試OK後，推到GitHub上

08.因為在舊的repo中設定過網域，要先取消舊的，然後在新的repo的setting裡設定網域

09.網域設定好後，GitHub會自動產生CNAME檔，這時遠端的進度超前了

10.先把遠端的pull下來，merge後，才能再推新的上去

11.連到原先的網址就可以看到已經換成新的佈景主題了

現在文章數還不多，所以還能這樣搬，
如果文章太多的話，可能要找其他更有效率的方法。
以上。

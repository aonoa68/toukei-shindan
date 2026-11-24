# 第11回　テキストマイニングに関する演習

歴代首相の所信表明演説を題材に、Python で名詞の頻度抽出、対応分析、ワードクラウドを行う演習です。データの出典と、KH Coder など関連ツールの利用上の注意も示します。

!!! note "この回について"
    演習ノートブックはスライド内のリンク先（Google Colaboratory）にあります。

## 資料

- :material-presentation: [スライド](files/week11-slides.pdf) <small>（8ページ・526 KB・一部ページ省略）</small>
- :material-table: [データ（abe2017.txt・所信表明演説 安倍首相 2017年）](files/week11/abe2017.txt) <small>（11 KB）</small>
- :material-table: [データ（abe2018.txt・所信表明演説 安倍首相 2018年）](files/week11/abe2018.txt) <small>（19 KB）</small>
- :material-table: [データ（abe2019.txt・所信表明演説 安倍首相 2019年）](files/week11/abe2019.txt) <small>（17 KB）</small>
- :material-table: [データ（suga.txt・所信表明演説 菅首相 2020年）](files/week11/suga.txt) <small>（21 KB）</small>
- :material-table: [データ（kishida2021.txt・所信表明演説 岸田首相 2021年）](files/week11/kishida2021.txt) <small>（21 KB）</small>
- :material-table: [データ（kishida2022.txt・所信表明演説 岸田首相 2022年）](files/week11/kishida2022.txt) <small>（24 KB）</small>
- :material-table: [データ（kishida2023.txt・所信表明演説 岸田首相 2023年）](files/week11/kishida2023.txt) <small>（25 KB）</small>
- :material-table: [データ（ishiba2024-1.txt・所信表明演説 石破首相 2024年(1)）](files/week11/ishiba2024-1.txt) <small>（28 KB）</small>
- :material-table: [データ（ishiba2024-2.txt・所信表明演説 石破首相 2024年(2)）](files/week11/ishiba2024-2.txt) <small>（26 KB）</small>
- :material-table: [データ（takaichi.txt・所信表明演説 高市首相 2025年）](files/week11/takaichi.txt) <small>（23 KB）</small>
- :material-check-circle-outline: [課題の解答例](files/week11-answer.pdf) <small>（1ページ・355 KB）</small>

<small>「一部ページ省略」とある資料は、公開にあたって授業運営の連絡や一部の図版のページを省いています。そのためページ番号が授業時のものと合わない箇所があります。</small>

## スライドをこのページで見る

<iframe class="pdf-frame" src="../files/week11-slides.pdf" title="スライド" loading="lazy"></iframe>

<small>表示されない場合は、上の「資料」のリンクから PDF を開いてください。</small>

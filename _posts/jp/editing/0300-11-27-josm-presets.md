---
layout: doc
title: JOSMプリセット
permalink: /jp/editing/josm-presets/
lang: jp
category: editing
---

JOSMプリセット
============
JOSMを触っているうちに、タグとプリセットをなんとなく理解できるようになってくるかと思います。すべてのオブジェクトは、2つの要素から成り立っています。1つはジオメトリ(つまり、ポイントやライン、シェイプといったオブジェクトの種別と、その位置情報)。そして2つめは、タグ情報としてあらわされる、そのオブジェクトの属性情報です。

オブジェクトを選択し、そこにプリセットメニューから情報の選択を行うことによって、そのオブジェクトに対して正しいタグが自動的に割り当てられます。

プリセットを利用するにあたって、そのメニューにない項目を追加したい場合、あるいは、自分でタグをカスタマイズしたい場合はどうすればよいでしょうか？

この場合、プリセットメニューに自分で項目をカスタマイズして追加することが可能です。このセクションでは、その方法を紹介します。[次の章](/jp/editing/creating-presets)の内容では、自分自身でプリセットファイル自体を作成する方法をカバーします。

プリセット追加
-----------
プリセットで表示されるメニューとサブメニューは、それぞれのプリセット毎の設定ファイルに、項目とフォームが記載されています。それぞれの項目を選んだ際に適用されるタグを定義しているのも、このファイルです。

オンラインで公開されている情報をプリセットファイルに追加したり、コンピュータに保存してJOSMで利用できるようにすることはとても簡単です。

-	プリセットメニューに項目を追加するには、JOSMを起動し、編集 -> 環境設定 を選択します。
-	上から3つめ、地球の上をグリッドが覆っている形のタブをクリックします。

![tagging presets tab][]

-	"タグ付けプリセット"のタブをクリックします。

![tagging presets menu][]

-	ウェブ上で公開されているプリセットファイルを追加するには、左側に表示されているリストから対象のプリセットを選択し、青い矢印をクリックしてください。例えば、"Buildings Indonesia by Kate Chapman"というプリセットを追加するとします。

![example presets][]

-	右側のリストに、対象の項目が表示されます。
-	OKをクリックしてください。
-	JOSMの再起動を行います。
-	レイヤを新規作成し、ポイントかシェイプを作成してください。
-	プリセットメニューを選択し、メニューの一番下にある、今回追加された"Building"という項目をクリックします。

![indonesia building form][]

-	インドネシア語がわからない場合、そこで表示される文字を読み取ることは難しいかもしれません。ただ、この作業で、対象のプリセットを読み込むことに成功したことは確かです。

-	独自に作成したプリセットファイルがある場合、同じ方法でメニューからそのファイルを追加することが可能です。環境設定項目をもういちど表示させ、リストから項目を選択するのではなく、右上に表示されている (+) ボタンをクリックしてください。

![plus button][]

-	ファイルが格納されている場所を指定し、JOSM上で表示される名前を入力します。
-	OKをクリックしてください。


[tagging presets tab]: /images/jp/editing/josm-presets/tagging-presets-tab.png
[tagging presets menu]: /images/jp/editing/josm-presets/tagging-presets-menu.png
[example presets]: /images/jp/editing/josm-presets/example-presets.png
[indonesia building form]: /images/jp/editing/josm-presets/indonesia-building-form.png
[plus button]: /images/jp/editing/josm-presets/plus-button.png


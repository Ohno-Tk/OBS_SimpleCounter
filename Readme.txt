■設置方法
01.htmlは全て表示サイズを横300px×高さ150pxにしてください。

input,htmlは表に出さないので、レイヤーの一番下に配置してください。
表示サイズは横750px×高さ620pxにしてください。

■カスタマイズ方法
・インプット側
input.html内の名称を変更することが出来ます。

変更方法は、OBSのカスタムCSSに以下のCSSを記載します。

:root {
--user_01:"変更したい名称";
}

・表示側
表示側はフォントサイズと色、背景色を設定する事ができます。

変更方法は、OBSのカスタムCSSに以下のCSSを記載します。

:root {
--font_size: 100px;
--font_color: #000;
--background: #fff;
}

背景を透過にしたい場合は、
:root {
--background : transparent;
}
に設定してください。背景がなくなります。
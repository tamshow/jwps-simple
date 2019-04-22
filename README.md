## 環境構築

CSS,JS等のビルドはツールを使用しています。
マシン環境に合わせて設定をしてください。

また書き出しツールは次をルートと設定してください。

```
frontend
```


### Macの方
「CodeKit」

```
frontend/config.codekit3
```

https://codekitapp.com/

有料版、無料版（制限付）あり

設定を変更する場合は有料版が必要になりますが
無料トライアル期間後「読み取り専用モード」となりコンパイルは無料で使用可能です。
https://codekitapp.com/help/read-only/



### Windowsの方
「Prepros」


```
frontend/prepros-6.config
```

https://prepros.io/

有料版、無料版あり

無料で使用すると定期的にライセンスの購入に関する表示が出現します。
有料版にすることで非表示になります。

### ツールを使用しない方

次の書き出しを環境を整えてください。

sass

```
/assets/sass/bundle.scss
↓
/assets/css/bundle.css
```

js

```
/assets/js/main.js

↓
/assets/js/main.min.js
```



## 使用ツール

次のCSSツールを読み込んでいます。
https://www.bourbon.io/
https://github.com/thoughtbot/neat
https://necolas.github.io/normalize.css/

# Java_api
## JavaのAPIについてまとめていく
### JavaのAPI（Application Programming Interface ）
Javaでアプリケーションを作成するために必要となる標準機能を提供するインタフェースのこと。  
Javaの機能を有効に使うためにはAPIの使用が必須。  
開発者はJavaのルールに従ってAPIを使用することにより、自分で1から実装することなく用意されたAPIを使用することで効率よく開発することができる。  
例えば、以下のようにコンソールに文字列を出力するおなじみの処理も、Javaが提供しているAPIを使用。  
```
System.out.println("Hello World");
```
これは、Systemクラスのoutというクラスフィールドを取得し、outクラスフィールドで使用できるprintlnメソッドを呼出して、引数で指定された変数や文字列を出力するJavaのAPI。  

### Spring Boot
JavaでAPIを使うためには、Javaのフレームワークである「Spring Boot」を使う。  
この他のフレームワークである「Spring Framework」もあるが、こちらは便利で機能が豊富な一方で機能の使い分けが困難というデメリットがある。  
このようなデメリットを克服するために作られたのが、「Spring Boot」。「　Spring Framework」で複数の機能を利用する場合に必要となるBean定義やXML設定を可能な限り自動設定する機能がある。  
なお、「Spring Boot」は「Spring Framework」を構成する１つとして搭載されている。

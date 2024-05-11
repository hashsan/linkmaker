# linkmaker
リンクメーカーは、テンプレートを設定することで、ホームページを作成できるものです。
template.htmlを設定すると、それを元に、どんどん、新しいページを作成します。
新しいページの作成は、内部リンクを設定することです。
内部リンクを単純に設定し、エディタモードにすることで、リンクがない場合は、クリックした時に新しいページを作成します。

## 自発的にページを作る場合
template.html?q=page2.html
とすると、page2.htmlが作成されそのページに飛びます。拡張子.htmlがない場合も自動で付与されます。

## 現在のページの編集
現在のページを「page2.html」として、そのページを編集する場合は?editをつけます。イコールの後ろは何でも構いません。
page2.html?edit=1000
とすると編集できます。
編集は、画面の右端にエディタが表示されるのでわかります。


## リンクメーカー

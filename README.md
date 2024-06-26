# item_modifier-set_stew_effect
item_modifierの1項目であるset_stew_effectに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】set_stew_effectで怪しげなシチューに効果付与【item_modifier】](https://natsumake.com/item_modifier-set_stew_effect/)』を参考にしてください。

<h3>概要</h3>
怪しげなシチューに対して、エフェクトを付与します。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、怪しげなシチューをドロップします。<br>
この怪しげなシチューを食べることで、跳躍力上昇のエフェクトが付与されます。<br>
効果時間は短いため、画面左上のエフェクトアイコンで確認するのがおすすめです。

また、手元に怪しげなシチューを持った状態で以下のコマンドを実行することで、発光のエフェクトが付与されるものに変化します。

```copy
/item modify entity @s weapon.mainhand sample:set_stew_effect
```

※すでにエフェクトが付与されている怪しげなシチューに適用させた場合は、そのエフェクトに加えて発光するようになります。

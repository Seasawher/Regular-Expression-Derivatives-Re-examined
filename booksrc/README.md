# Regular Expression Derivatives Re-examined

原文: <https://www.cambridge.org/core/services/aop-cambridge-core/content/view/E5734B86DEB96C61C69E5CF3C4FB0AFA/S0956796808007090a.pdf/regular-expression-derivatives-re-examined.pdf>

## 要約
正規表現の導関数は、正規表現を決定性有限オートマトンにコンパイルするための古くからあるエレガントな技法です。この技法は、交差や補集合などのブール演算子を正規表現演算子に拡張することを容易にサポートします。しかし、残念ながら、この技法は時の砂に埋もれてしまい、ほとんどのコンピュータ科学者はそれを知りません。
本論文では、正規表現の導関数を再検討し、2つの異なる関数型言語実装の文脈での経験を報告します。基本的な実装はシンプルであり、大規模な文字セット（例：Unicode）を扱うためにどのように拡張するかを示します。また、導関数アプローチがMcNaughtonとYamadaによって与えられた従来のアルゴリズムよりも小さな状態機械を導くことを示します。
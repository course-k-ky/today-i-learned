## 配列に対するバリデーション
### array.compact()
falsyな値を除外してくれる
カスタムの関数をcompact内に定義することも可能
ある条件に合致するものだけ除外、ということができる
定義する関数はbooleanを戻り値として返せばよい

testで親の配列を取得する方法
```
.test('unique', 'キーワードは一意である必要があります', function (value) {

const { parent } = this;

return parent.filter((keyword: string) => keyword === value).length <= 1;

})
```


### 特殊なプロパティ
parentとfrom
ofとかtestとかで参照できるものが違う
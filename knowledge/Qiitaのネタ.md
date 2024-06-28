### MUIのModalを使うとき、カスタムコンポーネントを使うと警告が出る
Warning: Failed prop type: Invalid prop `children` supplied to `ForwardRef(Modal4)`. Expected an element that can hold a ref. Did you accidentally use a plain function component for an element instead? For more information see [https://mui.com/r/caveat-with-refs-guide](https://mui.com/r/caveat-with-refs-guide)

### S3バケットに静的サイト上げるの苦労した話
画像ソースの指定方法
/ではなく./
tsconfig.jsonの"baseUrl": ".",
vite.config.tsのbase: "./",
package.jsonのhomepage:"./"

```React
<BrowserRouter basename="./">
```
s3のホスティングとreact-routerは相性が悪いらしい
https://qiita.com/kurakura-t/items/74bd4e7951e3114126fd

色々設定が必要
### ReactRouterでどうやってルーティングしているか
https://blog.ojisan.io/s3-spa-deploy/

https://sb-blog.link/archives/281

https://qiita.com/seapolis/items/0afd49d24b12749d93ab

### /と/index.htmlのちがい

### eventのtargetとcurrentTargetの違い
valueが取れたりとれなかったりする
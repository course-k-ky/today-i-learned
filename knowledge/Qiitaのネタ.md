### MUIのModalを使うとき、カスタムコンポーネントを使うと警告が出る
Warning: Failed prop type: Invalid prop `children` supplied to `ForwardRef(Modal4)`. Expected an element that can hold a ref. Did you accidentally use a plain function component for an element instead? For more information see [https://mui.com/r/caveat-with-refs-guide](https://mui.com/r/caveat-with-refs-guide)

### S3バケットに静的サイト上げるの苦労した話
画像ソースの指定方法
/ではなく./
tsconfig.jsonの"baseUrl": ".",
vite.config.tsのbase: "./",
## 今回のまとめ
### Reactでwebアプリを作るなら
```
yarn init
yarn create react-app アプリ名
```
### アプリを走らせるなら
```
yarn start
```
### src内のコンポーネントを、以下の書き方で作成していく
```
import React from "react";
import コンポーネント from "コンポーネントまでのパス";
export default class コンポーネント名 extends React.Component {
    render() {
        return(html部分)
    }
}
```
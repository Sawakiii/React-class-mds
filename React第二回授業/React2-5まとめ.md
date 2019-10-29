## 今回のまとめ
### stateとpropsの基本
stateは全体を管理するコンポーネントでのみ変更可能。
propsは親コンポーネントから渡されるデータで、変更不可。

stateはクラスで記述するコンポーネント内では、以下の型で定義する。
```
：
constructor() {
    super()
    this.state = {}
}
：
```
stateをpropsとして子コンポーネントに受け渡すには、プロパティの形で渡す。

### stateとpropsの応用
stateを更新する時は、現在のstateをコピーして、this.setState()で更新する。
子コンポーネントがstateを更新するメソッドを使用する場合は、親コンポーネントからthis.メソッド名.bind(this)で渡す。




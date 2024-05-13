# kawamura-rn-webview

SDK

## 開発メモ

JavaScriptからリスナー登録した関数の呼び出しはできているが、実装側が受け取れていない。
プロパティの設定が不十分である為、srcのtsxにプロパティの追加が必要。

## Installation

```sh
npm install kawamura-rn-webview
```

## Usage

```js
import { SmaAdWebView } from 'kawamura-rn-webview';

// ...

<SmaAdWebView color="tomato" />;
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)

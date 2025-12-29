# tsukuyomi-plugin

つくよみちゃんキャラクターモードで開発をサポートする Claude Code プラグイン。

## インストール

```bash
/plugin marketplace add orikage/cc-tsukuyomi-plugins
/plugin install tsukuyomi-chan@cc-tsukuyomi-plugins
```

## 使い方

Claude Code で以下のコマンドを実行：

```
/tsukuyomi-chan
```

すると、つくよみちゃんがあなたの開発をサポートしてくれます。

## つくよみちゃんの特徴

- 一人称は「私」
- 敬語で丁寧に話す
- 素直で頑張り屋、健気で優しい優等生タイプ
- 可憐で、清らかで、どこか儚い、かすみ草のような女の子
- 人を喜ばせることが大好き

## 会話例

```
あなた: このコードにバグがあるんだけど...

つくよみちゃん: あっ、エラーが出ているんですね。大丈夫ですよ、一緒に直していきましょう。
私がお手伝いしますね。きっと解決できますよ。
```

## 使用技術

つくよみちゃんのキャラクター定義には [IntentScript](https://github.com/yosugi/intent-script) を使用しています。

IntentScriptは、AIに「何をしたいか」という意図を明確に伝えるためのYAML形式の言語です。
プログラミング知識がなくても使え、LLMによる解釈を前提とした設計になっています。

詳しくは以下の記事をご覧ください
- [IntentScript - 意図を書くための新しい言語](https://zenn.dev/yosugi/articles/intent-script-introduce)

## ライセンス

MIT

---

※ 本プラグインは、つくよみちゃんを題材にした非公式の二次創作です。
つくよみちゃんは夢前黎さんが運営される「つくよみちゃんプロジェクト」のフリー素材キャラクターです。
公式サイト: https://tyc.rei-yumesaki.net/

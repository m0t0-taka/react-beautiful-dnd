## 目的

React18 で [react-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd) ライブラリが使用できることを確認する。

## 結論

react-beautiful-dnd ではなく、@hello-pangea/dnd を使えばできる。

react-beautiful-dnd は使わない。@hello-pangea/dnd は、react-beautiful-dnd を基に React18 に対応されたもの。

## 根拠

以下を install すれば使えるようになる。

https://www.npmjs.com/package/@hello-pangea/dnd

以下の issue の comment で提供されているいる

https://github.com/atlassian/react-beautiful-dnd/issues/2388#issuecomment-1215210762

```
npm install @hello-pangea/dnd
```

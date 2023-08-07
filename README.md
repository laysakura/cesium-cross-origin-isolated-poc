# cesium-cross-origin-isolated-poc

CesiumJSをクロスオリジン分離環境で使えるかのPoC。

[CesiumJS Quickstart](https://cesium.com/learn/cesiumjs-learn/cesiumjs-quickstart/) の内容を実施。

クロスオリジン分離については ["Spectre の脅威とウェブサイトが設定すべきヘッダーについて"](https://blog.agektmr.com/2021/11/browser-security.html) の記事が詳しい。

## アクセス方法

<https://laysakura.github.io/cesium-cross-origin-isolated-poc/?accessToken=xxx>

ただし、 `accessToken` クエリパラメーターには[自身のCesium ionのアクセストークン](https://ion.cesium.com/tokens)を指定すること。

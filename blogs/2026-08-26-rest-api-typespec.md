---
title: "REST APIにTypeSpecを導入してスキーマ駆動開発"
url: "https://tech.layerx.co.jp/entry/typespec-in-aiworkforce"
date: "2026-08-26"
author: "ninjinkun"
feed_url: "https://tech.layerx.co.jp/feed"
---
Ai Workforce （以下AiW）を開発しているフロントエンドエンジニアのid:ninjinkunです。AiWではサーバーとフロントエンドの通信にREST APIを使っています。これまではサーバーサイドのFastAPI（Python）からOpenAPI Specを出力してクライアントコードの自動生成を行うフローはあったものの、サーバーサイドの実装が完了しないとフロントエンドの実装が始められない課題がありました。 私はGraphQLを利用した経験が長かったため、APIスキーマを実装前に定義し、フロントエンドとバックエンドがスキーマを使って並行で開発を行うスキーマ駆動開発をAiWにも持ち込み…

---
title: "SnowflakeのRow Access Policyをdbtで漏れなく適用する"
url: "https://tech.layerx.co.jp/entry/dbt-snowflake-rap-enforcement"
date: "2026-08-14"
author: "civitaspo"
feed_url: "https://tech.layerx.co.jp/feed"
---
こんにちは。バクラク事業部 BizOps部 データグループの@civitaspoです。 この記事では、Snowflake の Row Access Policy を dbt の実行フローの中で適用し続けるために作った dbt package、dbt-snowflake-rap-enforcement を紹介します。 github.com 以前紹介した dbt-authorized-models が dbt モデル間の参照可否を検査する package だった1のに対し、今回は Snowflake の行レベルアクセス制御を dbt モデルの定義どおりに維持するための package です。 はじ…

---
title: "Two Forms of Pre-rendering"
date: "2020-01-01"
---

Next.js には 2 つのプリレンダリングの形式があります。**Static Generation**と**Server-side Rendering**です。その違いは、ページの HTML を生成する**タイミング**にあります。

- **Static Generation**は、**ビルド時**に HTML を生成するプリレンダリング方法です。プリレンダリングされた HTML は、リクエストごとに再利用されます。
- **Server-side Rendering**は、**リクエストごとに**HTML を生成するプリレンダリング手法です。

重要なのは、Next.js では、各ページで使用するプリレンダリングの形式を**選択**できることです。ほとんどのページでは静的生成を使用し、その他のページではサーバーサイドレンダリングを使用することで、「ハイブリッド」な Next.js アプリを作成することができます。

class: middle, center
# deno の歴史

---
# 自己紹介

- @kt3k という名前で github / twitter やってます
- フリーランス、フロントエンドエンジニア (react, vue)

---

# Go prototype 時代

- [2018/05/14](https://github.com/denoland/deno/commit/f7c5e19081920f59ce2006d3255a58fb611b6a17) - 2018/06
- JSConf EU で deno 発表 (2018/06/02)
  - [10 Things I Regret About Node.js](https://www.youtube.com/watch?v=M3BM9TB-8yA)
- Chinese Trolling Boom [例](https://github.com/denoland/deno/issues/189)
- [Double GC が懸念](https://github.com/denoland/deno/issues/205#issuecomment-397130413)となりGo prototype は削除される

---

# Rust rewrite 時代

- [2018/06/10](https://github.com/denoland/deno/commit/110ddab670cbf477488cceeea2842c980942d7b8) - 2018/08
- 一旦全てリセット
- go バージョンに contribute してた人々去る
- [ProtoBuf -> FlatBuffers](https://github.com/denoland/deno/issues/269#issuecomment-404668371)
- V8 Snapshot 整備, [parcel -> rollup 移行](https://github.com/denoland/deno/pull/395)などインフラの整備が進捗
- [自分がコントリビュート始めた](https://github.com/denoland/deno/pull/309)時期

---

# v0.1.x 時代

- [2018/08/23](https://github.com/denoland/deno/releases/tag/v0.1.0) - 2018/11
- API 類がモリモリ実装される
- [net 実装](https://github.com/denoland/deno/pull/884)
- [継続的ベンチマーク開始](https://github.com/denoland/deno/pull/777)

---

# v0.2.x 時代

- [2018/11/16](https://github.com/denoland/deno/releases/tag/v0.2.0) - 現在
- [deno_std](https://github.com/denoland/deno_std) が出来る
  - 開発の比重が deno_std 側に傾く
- [AMD -> Native Module移行](https://github.com/denoland/deno/pull/1460)
- Deno Boom in Japan (2018/12 -)

---

# 未来 (私見です)

- WASM サポート
- dev.jspm.io 互換性 (-> 出来ると babel とか動くかも)
- etc...

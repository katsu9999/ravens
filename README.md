# Ravens — Court Shuffle

https://katsu9999.github.io/ravens/

Ravens 用のコート割り振りアプリの公開場所。アプリ本体は
[katsu9999/gg-tennis](https://github.com/katsu9999/gg-tennis)。ここにはコードを置かず、
GG で公開に成功した版を Ravens 専用（`VITE_FIXED_CLUB=ravens`）でビルドして公開するだけ。

- 更新: 30分ごとに自動。すぐ反映するときは Actions → "Deploy Ravens" → Run workflow
- 必要な Secrets: `VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY`（GG と同じ公開用の値）
- データ: 同じ Supabase の Ravens クラブ分だけ。GG のデータは見えない

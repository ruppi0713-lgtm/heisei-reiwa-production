# heisei-reiwa-production

「平成さんと令和さん」（平成 vs 令和をくらべる、ゆる3D動画）の制作リポジトリです。非公開。
山下達郎（Muse）が台本・指示・テンプレを入れ、Codex（デスクトップ版／ウェブ版どちらでも）が読んで制作し、成果物をここへ返す、受け渡しの場所です。

## 流れ

```
1. 山下達郎が scripts/ に台本・Codexパックを入れる
2. ちあきが Codex に「このリポジトリの指示で作って」と言う
3. Codex が制作し、成果物の記録を outputs/ へ返す
4. 山下達郎が読んでチェックし、直しがあれば scripts/ に指示を足す
```

## 中身

- `AGENTS.md`
  Codexへのお願い。制作の前に必ず読むこと。固定ルール（声・色・テロップ・成果物の名前）はここが正本。
- `scripts/`
  話数ごとの台本とCodexパック、投稿SOP、実写版の設計メモ。
  - `ep01_codex_pack.md` / `ep02-04_script_pack.md` / `ep02-04_codex_pack.md` / `ep05-06_script_pack.md`
  - `posting_sop.md`（4媒体の投稿手順・キャプションの型）
  - `live_action_special_design.md`（月1回のAI実写版の設計）
- `templates/`
  使い回す制作テンプレの置き場（Motion Canvasのカウンター、Flubberの変形トランジション、Remotionの合成など）。中身の説明はフォルダ内のREADME。
- `outputs/`
  成果物の記録の置き場。何を・いつ・どの指示で作ったかを残す。大きな動画ファイル自体はここに入れない（理由はフォルダ内のREADME）。

## 注意

- 受講生の情報、クライアントの情報は入れない。入れるのは制作物と制作の型だけ。
- キャラの声・色・口癖などの固定事項は `AGENTS.md` と design-reference リポジトリのノートが正本。ここで勝手に変えない。

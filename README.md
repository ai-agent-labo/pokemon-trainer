# Pokemon Type Trainer (タイプ相性トレーニング)

ポケモン対戦の **タイプ相性を体に叩き込むための学習ゲーム**。
シンプルな 3v3 ミニバトルをループしながら、無効・半減・抜群・ちょうばつぐん の倍率反射を鍛える。

## 特徴

- **2 モード**: 単タイプ (18 体) / 複合タイプ (27 体、Champions DB プールから)
- **4 段階の難易度**: 観察 → 読み合い → リード読み → 大荒れ
- **スコアアタック**: 倍率別に得点、連勝倍率、完全勝利・ソロ突破ボーナス
- **演出**: シェイク + 画面シェイク (抜群) / レインボー演出 + 爆発 SE (ちょうばつぐん)
- **音**: CC0 Kenney + Juhani Junkala チップチューン BGM

## 開発

ローカル開発:

```bash
python3 -m http.server 8766
# → http://localhost:8766/
```

`index.html` だけの静的サイト。ビルド不要。

## デプロイ

Vercel に直接ホスティング (静的サイトとして):

- Framework Preset: Other
- Build Command: (なし)
- Output Directory: `.`

## ライセンス

- コード: MIT
- 効果音: CC0 ([Kenney.nl](https://kenney.nl/))
- BGM: CC0 ([Juhani Junkala / OpenGameArt](https://opengameart.org/content/5-chiptunes-action))
- ポケスプライト: [Pokémon Showdown](https://play.pokemonshowdown.com/) (外部 CDN 参照)
- タイプアイコン: Pokémon Champions DB プロジェクトから流用

---
marp: true
paginate: true
---

<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

<style>
:root {
  /* Primary */
  --color-primary: #0284c7;
  --color-primary-dark: #1e3a8a;
  --color-accent: #06b6d4;

  /* Text */
  --color-text: #111827;
  --color-text-sub: #6b7280;
  --color-text-muted: #9ca3af;
  --color-text-white: #ffffff;

  /* Background */
  --color-bg: #ffffff;
  --color-bg-card: #f3f4f6;
  --color-bg-info: #f0f9ff;
  --color-border: #d1d5db;

  /* Gradient */
  --gradient-primary: linear-gradient(135deg, var(--color-primary-dark), var(--color-primary), var(--color-accent));
  --gradient-accent: linear-gradient(135deg, var(--color-primary), var(--color-accent));

  /* Status */
  --color-success: #22c55e;
  --color-danger: #ef4444;
  --color-bg-success: #f0fdf4;
  --color-bg-danger: #fef2f2;

  /* Level shades (light to dark) */
  --color-primary-100: #f0f9ff;
  --color-primary-200: #e0f2fe;
  --color-primary-300: #bae6fd;
  --color-primary-400: #7dd3fc;
  --color-primary-500: #38bdf8;
  --color-primary-600: #0ea5e9;

  /* Phase backgrounds */
  --color-bg-phase1: #dbeafe;
  --color-bg-phase2: #e0f2fe;
  --color-bg-phase3: #cffafe;
  --color-bg-phase4: #dcfce7;
}
section {
  background-color: var(--color-bg);
  color: var(--color-text);
  font-family: system-ui, sans-serif;
}
section::after {
  color: var(--color-primary);
}
h1, h2, h3 {
  color: var(--color-primary);
}
</style>

<!-- ===== A. タイトル・セクション系 ===== -->

<!-- A1 タイトルスライド -->
<!-- _paginate: false -->

<style scoped>
section {
  background: var(--gradient-primary);
  color: var(--color-text-white);
}
</style>

<div class="flex flex-col justify-between h-full">
  <div class="flex flex-col justify-center flex-1 gap-6">
    <h1 class="text-6xl font-bold" style="color: var(--color-text-white);">
      プレゼンテーションタイトル
    </h1>
    <p class="text-2xl" style="color: var(--color-text-white);">
      サブタイトル
    </p>
  </div>
  <p class="text-xl self-end" style="color: var(--color-text-white);">
    発表者名
  </p>
</div>

---

<!-- A2 セクション開始スライド -->
<!-- _paginate: false -->

<style scoped>
section {
  background: var(--gradient-primary);
  color: var(--color-text-white);
}
</style>

<div class="flex flex-col items-center justify-center h-full gap-4">
  <h1 class="text-5xl font-bold" style="color: var(--color-text-white);">
    セクション名
  </h1>
</div>

---

<!-- A3 まとめスライド -->
<!-- _paginate: false -->

<style scoped>
section {
  background: var(--gradient-primary);
  color: var(--color-text-white);
}
</style>

<div class="flex flex-col justify-center h-full gap-6">
  <h2 class="text-4xl font-bold" style="color: var(--color-text-white);">
    まとめ
  </h2>
  <ul class="text-xl leading-loose list-disc pl-6" style="color: var(--color-text-white);">
    <li>ポイント1：主要な結論や要点をここに</li>
    <li>ポイント2：次のステップやアクション</li>
    <li>ポイント3：補足情報やリソース</li>
  </ul>
</div>

---

<!-- A-基本コンテンツスライド -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  コンテンツの見出し
</h2>

<div class="text-xl leading-relaxed" style="color: var(--color-text);">
  <p class="mb-4">
    ここに本文テキストが入ります。スライドの標準的なレイアウトで、見出しと本文テキストを組み合わせたコンテンツスライドです。
  </p>
  <p>
    複数の段落を使って、内容を分かりやすく伝えることができます。重要なポイントは<strong style="color: var(--color-primary);">強調表示</strong>で目立たせましょう。
  </p>
</div>

---

<!-- A4 目次スライド -->

<h2 class="text-4xl font-bold mb-10" style="color: var(--color-primary);">
  目次
</h2>

<div class="flex flex-col gap-4 text-xl">
  <div class="flex items-center gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold text-lg" style="background-color: var(--color-primary);">1</span>
    <span style="color: var(--color-text);">はじめに</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold text-lg" style="background-color: var(--color-primary);">2</span>
    <span style="color: var(--color-text);">課題と背景</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold text-lg" style="background-color: var(--color-primary);">3</span>
    <span style="color: var(--color-text);">提案内容</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold text-lg" style="background-color: var(--color-primary);">4</span>
    <span style="color: var(--color-text);">実装計画</span>
  </div>
  <div class="flex items-center gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold text-lg" style="background-color: var(--color-primary);">5</span>
    <span style="color: var(--color-text);">まとめ</span>
  </div>
</div>

---

<!-- A5 クロージングスライド -->
<!-- _paginate: false -->

<style scoped>
section {
  background: var(--gradient-primary);
  color: var(--color-text-white);
}
</style>

<div class="flex flex-col items-center justify-center h-full gap-8">
  <h1 class="text-6xl font-bold" style="color: var(--color-text-white);">
    Thank You
  </h1>
  <p class="text-2xl" style="color: var(--color-text-white);">
    ご清聴ありがとうございました
  </p>
</div>

---

<!-- ===== B. カラムレイアウト系 ===== -->

<!-- B5 2カラムレイアウト（既存） -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  2カラムレイアウト
</h2>

<div class="grid grid-cols-2 gap-8">
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-primary);">左カラム</h3>
    <p class="text-sm" style="color: var(--color-text);">
      左側のコンテンツをここに配置します。テキスト、画像、リストなど自由に使えます。
    </p>
  </div>
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-primary);">右カラム</h3>
    <p class="text-sm" style="color: var(--color-text);">
      右側のコンテンツをここに配置します。左右で対比や補足を表現できます。
    </p>
  </div>
</div>

---

<!-- B6 Before/After比較 -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  Before / After
</h2>

<div class="grid grid-cols-2 gap-8">
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-primary);">Before</h3>
    <ul class="text-sm list-disc pl-4" style="color: var(--color-text);">
      <li>課題や問題点を記載</li>
      <li>改善前の状況</li>
      <li>非効率なプロセス</li>
    </ul>
  </div>
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-primary);">After</h3>
    <ul class="text-sm list-disc pl-4" style="color: var(--color-text);">
      <li>解決された状態を記載</li>
      <li>改善後の状況</li>
      <li>効率化されたプロセス</li>
    </ul>
  </div>
</div>

---

<!-- B7 2カラム対比（Pro/Con） -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  メリット・デメリット
</h2>

<div class="grid grid-cols-2 gap-8">
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-success); border-left: 4px solid var(--color-success);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-success);">メリット</h3>
    <ul class="text-sm list-disc pl-4" style="color: var(--color-text);">
      <li>利点の説明1</li>
      <li>利点の説明2</li>
      <li>利点の説明3</li>
    </ul>
  </div>
  <div class="p-6 rounded-lg" style="background-color: var(--color-bg-danger); border-left: 4px solid var(--color-danger);">
    <h3 class="text-xl font-bold mb-4" style="color: var(--color-danger);">デメリット</h3>
    <ul class="text-sm list-disc pl-4" style="color: var(--color-text);">
      <li>欠点の説明1</li>
      <li>欠点の説明2</li>
      <li>欠点の説明3</li>
    </ul>
  </div>
</div>

---

<!-- B8 3カラム等幅 -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  3カラムレイアウト
</h2>

<div class="grid grid-cols-3 gap-6">
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-primary);">カラム1</h3>
    <p class="text-sm" style="color: var(--color-text);">
      1つ目のコンテンツをここに配置します。
    </p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-primary);">カラム2</h3>
    <p class="text-sm" style="color: var(--color-text);">
      2つ目のコンテンツをここに配置します。
    </p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-primary);">カラム3</h3>
    <p class="text-sm" style="color: var(--color-text);">
      3つ目のコンテンツをここに配置します。
    </p>
  </div>
</div>

---

<!-- B9 3カラムアクセント -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  3カラム（中央アクセント）
</h2>

<div class="grid grid-cols-3 gap-6">
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-primary);">ベーシック</h3>
    <p class="text-sm" style="color: var(--color-text);">基本プランの説明をここに記載します。</p>
  </div>
  <div class="p-5 rounded-lg text-white" style="background: var(--gradient-accent);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-text-white);">おすすめ</h3>
    <p class="text-sm" style="color: var(--color-text-white);">推奨プランの説明をここに記載します。</p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-lg font-bold mb-3" style="color: var(--color-primary);">プレミアム</h3>
    <p class="text-sm" style="color: var(--color-text);">上位プランの説明をここに記載します。</p>
  </div>
</div>

---

<!-- B10 4カラム -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  4カラムレイアウト
</h2>

<div class="grid grid-cols-4 gap-4">
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目1</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキスト</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目2</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキスト</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目3</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキスト</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目4</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキスト</p>
  </div>
</div>

---

<!-- B11 5カラム成熟度レベル -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  成熟度レベル
</h2>

<div class="grid grid-cols-5 gap-3">
  <div class="p-3 rounded-lg text-center" style="background-color: var(--color-bg-info);">
    <div class="text-sm font-bold mb-1" style="color: var(--color-primary-400);">Level 1</div>
    <div class="text-xs font-bold mb-2" style="color: var(--color-text);">初期</div>
    <p class="text-xs" style="color: var(--color-text);">未整備の状態</p>
  </div>
  <div class="p-3 rounded-lg text-center" style="background-color: var(--color-primary-200);">
    <div class="text-sm font-bold mb-1" style="color: var(--color-primary-500);">Level 2</div>
    <div class="text-xs font-bold mb-2" style="color: var(--color-text);">反復</div>
    <p class="text-xs" style="color: var(--color-text);">部分的に実施</p>
  </div>
  <div class="p-3 rounded-lg text-center" style="background-color: var(--color-primary-300);">
    <div class="text-sm font-bold mb-1" style="color: var(--color-primary-600);">Level 3</div>
    <div class="text-xs font-bold mb-2" style="color: var(--color-text);">定義</div>
    <p class="text-xs" style="color: var(--color-text);">標準化済み</p>
  </div>
  <div class="p-3 rounded-lg text-center" style="background-color: var(--color-primary-400);">
    <div class="text-sm font-bold mb-1" style="color: var(--color-primary);">Level 4</div>
    <div class="text-xs font-bold mb-2" style="color: var(--color-text);">管理</div>
    <p class="text-xs" style="color: var(--color-text);">測定・管理</p>
  </div>
  <div class="p-3 rounded-lg text-center" style="background-color: var(--color-primary);">
    <div class="text-sm font-bold mb-1" style="color: var(--color-text-white);">Level 5</div>
    <div class="text-xs font-bold mb-2" style="color: var(--color-text-white);">最適化</div>
    <p class="text-xs" style="color: var(--color-text-white);">継続的改善</p>
  </div>
</div>

---

<!-- B12 2x2グリッド -->

<h2 class="text-4xl font-bold mb-6" style="color: var(--color-primary);">
  2×2 マトリクス
</h2>

<div class="grid grid-cols-2 gap-4">
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">象限1</h3>
    <p class="text-sm" style="color: var(--color-text);">重要度：高 / 緊急度：高</p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">象限2</h3>
    <p class="text-sm" style="color: var(--color-text);">重要度：高 / 緊急度：低</p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">象限3</h3>
    <p class="text-sm" style="color: var(--color-text);">重要度：低 / 緊急度：高</p>
  </div>
  <div class="p-5 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">象限4</h3>
    <p class="text-sm" style="color: var(--color-text);">重要度：低 / 緊急度：低</p>
  </div>
</div>

---

<!-- B13 2x3グリッド -->

<h2 class="text-4xl font-bold mb-6" style="color: var(--color-primary);">
  2×3 グリッド
</h2>

<div class="grid grid-cols-3 gap-4">
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目1</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目2</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目3</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目4</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目5</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card);">
    <h3 class="text-base font-bold mb-2" style="color: var(--color-primary);">項目6</h3>
    <p class="text-xs" style="color: var(--color-text);">説明テキストをここに記載します。</p>
  </div>
</div>

---

<!-- ===== C. 縦並びリスト系 ===== -->

<!-- C14 ステップ -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  ステップ
</h2>

<div class="flex items-start justify-between gap-2">
  <div class="flex-1 p-4 text-center">
    <span class="flex items-center justify-center w-12 h-12 rounded-full text-white font-bold text-xl mx-auto mb-3" style="background-color: var(--color-primary);">1</span>
    <h3 class="text-sm font-bold mb-1" style="color: var(--color-text);">ステップ1: 準備</h3>
    <p class="text-xs" style="color: var(--color-text-sub);">必要な情報とリソースを収集します。</p>
  </div>
  <div class="text-2xl font-bold self-center" style="color: var(--color-primary);">→</div>
  <div class="flex-1 p-4 text-center">
    <span class="flex items-center justify-center w-12 h-12 rounded-full text-white font-bold text-xl mx-auto mb-3" style="background-color: var(--color-primary);">2</span>
    <h3 class="text-sm font-bold mb-1" style="color: var(--color-text);">ステップ2: 実行</h3>
    <p class="text-xs" style="color: var(--color-text-sub);">計画に基づいて実行に移します。</p>
  </div>
  <div class="text-2xl font-bold self-center" style="color: var(--color-primary);">→</div>
  <div class="flex-1 p-4 text-center">
    <span class="flex items-center justify-center w-12 h-12 rounded-full text-white font-bold text-xl mx-auto mb-3" style="background-color: var(--color-primary);">3</span>
    <h3 class="text-sm font-bold mb-1" style="color: var(--color-text);">ステップ3: 検証</h3>
    <p class="text-xs" style="color: var(--color-text-sub);">結果を確認し、改善点を洗い出します。</p>
  </div>
</div>

---

<!-- C15 タイムライン -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  タイムライン
</h2>

<div class="flex flex-col gap-2">
  <div class="flex items-start gap-4">
    <div class="flex flex-col items-center">
      <div class="w-4 h-4 rounded-full" style="background-color: var(--color-primary);"></div>
      <div class="w-0.5 h-12" style="background-color: var(--color-border);"></div>
    </div>
    <div>
      <span class="text-sm font-bold" style="color: var(--color-primary);">2024年 Q1</span>
      <p class="text-sm" style="color: var(--color-text);">プロジェクト開始・要件定義</p>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <div class="flex flex-col items-center">
      <div class="w-4 h-4 rounded-full" style="background-color: var(--color-primary);"></div>
      <div class="w-0.5 h-12" style="background-color: var(--color-border);"></div>
    </div>
    <div>
      <span class="text-sm font-bold" style="color: var(--color-primary);">2024年 Q2</span>
      <p class="text-sm" style="color: var(--color-text);">設計・プロトタイプ開発</p>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <div class="flex flex-col items-center">
      <div class="w-4 h-4 rounded-full" style="background-color: var(--color-primary);"></div>
      <div class="w-0.5 h-12" style="background-color: var(--color-border);"></div>
    </div>
    <div>
      <span class="text-sm font-bold" style="color: var(--color-primary);">2024年 Q3</span>
      <p class="text-sm" style="color: var(--color-text);">実装・テスト</p>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <div class="flex flex-col items-center">
      <div class="w-4 h-4 rounded-full" style="background-color: var(--color-accent);"></div>
    </div>
    <div>
      <span class="text-sm font-bold" style="color: var(--color-accent);">2024年 Q4</span>
      <p class="text-sm" style="color: var(--color-text);">リリース・運用開始</p>
    </div>
  </div>
</div>

---

<!-- C16 アイコン付きリスト -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  特徴一覧
</h2>

<div class="flex flex-col gap-5">
  <div class="flex items-center gap-4">
    <span class="text-3xl">🚀</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">高速パフォーマンス</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">最適化されたアーキテクチャにより高速な処理を実現します。</p>
    </div>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-3xl">🔒</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">セキュリティ</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">最新のセキュリティ基準に準拠した堅牢な設計です。</p>
    </div>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-3xl">📱</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">マルチデバイス対応</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">あらゆるデバイスで最適な表示を提供します。</p>
    </div>
  </div>
  <div class="flex items-center gap-4">
    <span class="text-3xl">🔧</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">柔軟なカスタマイズ</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">ニーズに合わせた柔軟な設定が可能です。</p>
    </div>
  </div>
</div>

---

<!-- ===== E. 背景・画像系 ===== -->

<!-- E24 右側画像配置 -->

<div class="grid grid-cols-2 gap-8 h-full items-center">
  <div>
    <h2 class="text-3xl font-bold mb-6" style="color: var(--color-primary);">
      右側画像配置
    </h2>
    <p class="text-base mb-4" style="color: var(--color-text);">
      左側にテキストコンテンツ、右側に画像やビジュアルを配置するレイアウトです。
    </p>
    <p class="text-base" style="color: var(--color-text);">
      説明文と視覚素材を組み合わせて、わかりやすく情報を伝えることができます。
    </p>
  </div>
  <div class="flex items-center justify-center h-full rounded-lg" style="background-color: var(--color-bg-card); border: 2px dashed var(--color-border);">
    <span class="text-lg" style="color: var(--color-text-muted);">画像エリア</span>
  </div>
</div>

---

<!-- E25 左側画像配置 -->

<div class="grid grid-cols-2 gap-8 h-full items-center">
  <div class="flex items-center justify-center h-full rounded-lg" style="background-color: var(--color-bg-card); border: 2px dashed var(--color-border);">
    <span class="text-lg" style="color: var(--color-text-muted);">画像エリア</span>
  </div>
  <div>
    <h2 class="text-3xl font-bold mb-6" style="color: var(--color-primary);">
      左側画像配置
    </h2>
    <p class="text-base mb-4" style="color: var(--color-text);">
      左側に画像やビジュアル、右側にテキストコンテンツを配置するレイアウトです。
    </p>
    <p class="text-base" style="color: var(--color-text);">
      視覚素材を先に見せてから説明する流れを作ることができます。
    </p>
  </div>
</div>

---

<!-- E26 引用スライド -->

<div class="flex flex-col items-center justify-center h-full gap-6 px-12">
  <div class="text-8xl" style="color: var(--color-primary); line-height: 1;">❝</div>
  <p class="text-2xl text-center leading-relaxed italic" style="color: var(--color-text);">
    優れたデザインとは、できるだけ少ないデザインのことである。
  </p>
  <p class="text-lg" style="color: var(--color-text-sub);">
    — Dieter Rams
  </p>
</div>

---

<!-- ===== F. 強調・特殊系 ===== -->

<!-- F27 統計・数値強調 -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  主要指標
</h2>

<div class="grid grid-cols-3 gap-8 text-center">
  <div>
    <div class="text-5xl font-bold" style="color: var(--color-primary);">98%</div>
    <p class="text-base mt-2" style="color: var(--color-text-sub);">顧客満足度</p>
  </div>
  <div>
    <div class="text-5xl font-bold" style="color: var(--color-accent);">2.5x</div>
    <p class="text-base mt-2" style="color: var(--color-text-sub);">生産性向上</p>
  </div>
  <div>
    <div class="text-5xl font-bold" style="color: var(--color-primary-dark);">500+</div>
    <p class="text-base mt-2" style="color: var(--color-text-sub);">導入企業数</p>
  </div>
</div>

---

<!-- F28 中央配置キーメッセージ -->

<div class="flex flex-col items-center justify-center h-full gap-6">
  <h1 class="text-5xl font-bold text-center leading-tight" style="color: var(--color-primary);">
    シンプルさは究極の洗練である
  </h1>
  <p class="text-xl text-center" style="color: var(--color-text-sub);">
    複雑さを排除し、本質に集中する
  </p>
</div>

---

<!-- F29 Q&Aスライド -->
<!-- _paginate: false -->

<style scoped>
section {
  background: var(--gradient-primary);
  color: var(--color-text-white);
}
</style>

<div class="flex flex-col items-center justify-center h-full gap-6">
  <div class="text-8xl">🙋</div>
  <h1 class="text-5xl font-bold" style="color: var(--color-text-white);">
    Q & A
  </h1>
  <p class="text-xl" style="color: var(--color-text-white);">
    ご質問がありましたらお気軽にどうぞ
  </p>
</div>

---

<!-- ===== G. 応用パターン ===== -->

<!-- G30 QRコード -->

<h2 class="text-4xl font-bold mb-6" style="color: var(--color-primary);">
  詳細はこちら
</h2>

<div class="grid grid-cols-2 gap-8 items-center">
  <div>
    <p class="text-lg mb-4" style="color: var(--color-text);">
      QRコードを読み取って詳細情報にアクセスしてください。
    </p>
    <ul class="text-base list-disc pl-6" style="color: var(--color-text-sub);">
      <li>プロジェクトの詳細ドキュメント</li>
      <li>デモサイトへのリンク</li>
      <li>お問い合わせフォーム</li>
    </ul>
  </div>
  <div class="flex items-center justify-center">
    <div class="w-48 h-48 rounded-lg flex items-center justify-center" style="background-color: var(--color-bg-card); border: 2px dashed var(--color-border);">
      <span class="text-sm" style="color: var(--color-text-muted);">QRコード</span>
    </div>
  </div>
</div>

---

<!-- G31 問いかけスライド -->

<div class="flex flex-col items-center justify-center h-full gap-8">
  <div class="text-6xl">🤔</div>
  <h2 class="text-4xl font-bold text-center leading-snug" style="color: var(--color-primary);">
    もし、この課題を<br>半分の時間で解決できたら？
  </h2>
  <p class="text-lg text-center" style="color: var(--color-text-sub);">
    少し立ち止まって考えてみましょう
  </p>
</div>

---

<!-- G32 まとめ（番号付き） -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  Key Takeaways
</h2>

<div class="flex flex-col gap-5">
  <div class="flex items-start gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold shrink-0" style="background-color: var(--color-primary);">1</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">最も重要なポイント</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">プレゼンテーションの核心となるメッセージを記載します。</p>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold shrink-0" style="background-color: var(--color-primary);">2</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">次に重要なポイント</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">補足的な重要メッセージを記載します。</p>
    </div>
  </div>
  <div class="flex items-start gap-4">
    <span class="flex items-center justify-center w-10 h-10 rounded-full text-white font-bold shrink-0" style="background-color: var(--color-primary);">3</span>
    <div>
      <h3 class="text-lg font-bold" style="color: var(--color-text);">アクションアイテム</h3>
      <p class="text-sm" style="color: var(--color-text-sub);">聴衆に次に何をしてほしいかを明確に伝えます。</p>
    </div>
  </div>
</div>

---

<!-- G35 KPI/メトリクス -->

<h2 class="text-4xl font-bold mb-6" style="color: var(--color-primary);">
  KPI ダッシュボード
</h2>

<div class="grid grid-cols-4 gap-4">
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-info); border-top: 3px solid var(--color-primary);">
    <p class="text-sm mb-1" style="color: var(--color-text-sub);">月間売上</p>
    <div class="text-3xl font-bold" style="color: var(--color-primary);">¥12.5M</div>
    <p class="text-xs mt-1" style="color: var(--color-success);">▲ 15% 前月比</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-info); border-top: 3px solid var(--color-primary);">
    <p class="text-sm mb-1" style="color: var(--color-text-sub);">新規顧客</p>
    <div class="text-3xl font-bold" style="color: var(--color-primary);">248</div>
    <p class="text-xs mt-1" style="color: var(--color-success);">▲ 8% 前月比</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-info); border-top: 3px solid var(--color-primary);">
    <p class="text-sm mb-1" style="color: var(--color-text-sub);">継続率</p>
    <div class="text-3xl font-bold" style="color: var(--color-primary);">94.2%</div>
    <p class="text-xs mt-1" style="color: var(--color-success);">▲ 2.1% 前月比</p>
  </div>
  <div class="p-4 rounded-lg text-center" style="background-color: var(--color-bg-info); border-top: 3px solid var(--color-primary);">
    <p class="text-sm mb-1" style="color: var(--color-text-sub);">NPS</p>
    <div class="text-3xl font-bold" style="color: var(--color-primary);">72</div>
    <p class="text-xs mt-1" style="color: var(--color-danger);">▼ 3pt 前月比</p>
  </div>
</div>

---

<!-- G36 比較表 -->

<h2 class="text-4xl font-bold mb-4" style="color: var(--color-primary);">
  プラン比較
</h2>

<table class="w-full text-base" style="border-collapse: collapse;">
  <thead>
    <tr style="background-color: var(--color-primary); color: var(--color-text-white);">
      <th class="p-4 text-left">機能</th>
      <th class="p-4 text-center">ベーシック</th>
      <th class="p-4 text-center">スタンダード</th>
      <th class="p-4 text-center">プレミアム</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: var(--color-bg-card);">
      <td class="p-4 font-bold" style="color: var(--color-text);">ユーザー数</td>
      <td class="p-4 text-center" style="color: var(--color-text);">5名まで</td>
      <td class="p-4 text-center" style="color: var(--color-text);">50名まで</td>
      <td class="p-4 text-center" style="color: var(--color-text);">無制限</td>
    </tr>
    <tr>
      <td class="p-4 font-bold" style="color: var(--color-text);">ストレージ</td>
      <td class="p-4 text-center" style="color: var(--color-text);">10GB</td>
      <td class="p-4 text-center" style="color: var(--color-text);">100GB</td>
      <td class="p-4 text-center" style="color: var(--color-text);">1TB</td>
    </tr>
    <tr style="background-color: var(--color-bg-card);">
      <td class="p-4 font-bold" style="color: var(--color-text);">サポート</td>
      <td class="p-4 text-center" style="color: var(--color-text);">メール</td>
      <td class="p-4 text-center" style="color: var(--color-text);">チャット</td>
      <td class="p-4 text-center" style="color: var(--color-text);">24/7専用</td>
    </tr>
    <tr>
      <td class="p-4 font-bold" style="color: var(--color-text);">API連携</td>
      <td class="p-4 text-center" style="color: var(--color-text-muted);">—</td>
      <td class="p-4 text-center" style="color: var(--color-success);">✓</td>
      <td class="p-4 text-center" style="color: var(--color-success);">✓</td>
    </tr>
    <tr style="background-color: var(--color-bg-info);">
      <td class="p-4 font-bold" style="color: var(--color-text);">月額料金</td>
      <td class="p-4 text-center font-bold" style="color: var(--color-primary);">¥5,000</td>
      <td class="p-4 text-center font-bold" style="color: var(--color-primary);">¥15,000</td>
      <td class="p-4 text-center font-bold" style="color: var(--color-primary);">¥50,000</td>
    </tr>
  </tbody>
</table>

---

<!-- G37 ロードマップ -->

<h2 class="text-4xl font-bold mb-6" style="color: var(--color-primary);">
  ロードマップ
</h2>

<div class="flex gap-4">
  <div class="flex-1 p-4 rounded-lg" style="background-color: var(--color-bg-phase1); border-top: 4px solid var(--color-primary-dark);">
    <h3 class="text-sm font-bold mb-2" style="color: var(--color-primary-dark);">Phase 1</h3>
    <p class="text-xs font-bold mb-1" style="color: var(--color-text);">基盤構築</p>
    <p class="text-xs" style="color: var(--color-text-sub);">Q1 2024</p>
    <ul class="text-xs mt-2 list-disc pl-3" style="color: var(--color-text);">
      <li>要件定義</li>
      <li>アーキテクチャ設計</li>
    </ul>
  </div>
  <div class="flex-1 p-4 rounded-lg" style="background-color: var(--color-primary-200); border-top: 4px solid var(--color-primary);">
    <h3 class="text-sm font-bold mb-2" style="color: var(--color-primary);">Phase 2</h3>
    <p class="text-xs font-bold mb-1" style="color: var(--color-text);">MVP開発</p>
    <p class="text-xs" style="color: var(--color-text-sub);">Q2 2024</p>
    <ul class="text-xs mt-2 list-disc pl-3" style="color: var(--color-text);">
      <li>コア機能実装</li>
      <li>内部テスト</li>
    </ul>
  </div>
  <div class="flex-1 p-4 rounded-lg" style="background-color: var(--color-bg-phase3); border-top: 4px solid var(--color-accent);">
    <h3 class="text-sm font-bold mb-2" style="color: var(--color-accent);">Phase 3</h3>
    <p class="text-xs font-bold mb-1" style="color: var(--color-text);">ベータ版</p>
    <p class="text-xs" style="color: var(--color-text-sub);">Q3 2024</p>
    <ul class="text-xs mt-2 list-disc pl-3" style="color: var(--color-text);">
      <li>ベータリリース</li>
      <li>フィードバック収集</li>
    </ul>
  </div>
  <div class="flex-1 p-4 rounded-lg" style="background-color: var(--color-bg-phase4); border-top: 4px solid var(--color-success);">
    <h3 class="text-sm font-bold mb-2" style="color: var(--color-success);">Phase 4</h3>
    <p class="text-xs font-bold mb-1" style="color: var(--color-text);">正式リリース</p>
    <p class="text-xs" style="color: var(--color-text-sub);">Q4 2024</p>
    <ul class="text-xs mt-2 list-disc pl-3" style="color: var(--color-text);">
      <li>GA版公開</li>
      <li>マーケティング</li>
    </ul>
  </div>
</div>

---

<!-- G39 参考文献 -->

<h2 class="text-4xl font-bold mb-8" style="color: var(--color-primary);">
  参考文献
</h2>

<div class="flex flex-col gap-4">
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card); border-left: 3px solid var(--color-primary);">
    <p class="text-sm" style="color: var(--color-text);">
      <span class="font-bold">[1]</span> 著者名 (2024). 「論文・書籍タイトル」. 出版社/ジャーナル名, Vol.XX, pp.1-10.
    </p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card); border-left: 3px solid var(--color-primary);">
    <p class="text-sm" style="color: var(--color-text);">
      <span class="font-bold">[2]</span> 著者名 (2023). 「論文・書籍タイトル」. 出版社/ジャーナル名, Vol.XX, pp.11-20.
    </p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card); border-left: 3px solid var(--color-primary);">
    <p class="text-sm" style="color: var(--color-text);">
      <span class="font-bold">[3]</span> 著者名 (2023). 「Webページタイトル」. https://example.com （参照: 2024-01-01）
    </p>
  </div>
  <div class="p-4 rounded-lg" style="background-color: var(--color-bg-card); border-left: 3px solid var(--color-primary);">
    <p class="text-sm" style="color: var(--color-text);">
      <span class="font-bold">[4]</span> 著者名 (2022). 「技術レポートタイトル」. 組織名, Technical Report No.XX.
    </p>
  </div>
</div>

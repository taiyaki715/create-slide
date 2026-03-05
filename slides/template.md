---
marp: true
paginate: true
---

<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

<style>
section {
  background-color: #ffffff;
  color: #111827;
  font-family: system-ui, sans-serif;
}
section::after {
  color: #0284c7;
}
h1, h2, h3 {
  color: #0284c7;
}
</style>

<!-- _paginate: false -->

<style scoped>
section {
  background: linear-gradient(135deg, #1e3a8a, #0284c7, #06b6d4);
  color: #ffffff;
}
</style>

<div class="flex flex-col justify-between h-full">
  <div class="flex flex-col justify-center flex-1 gap-6">
    <h1 class="text-6xl font-bold" style="color: #ffffff;">
      プレゼンテーションタイトル
    </h1>
    <p class="text-2xl" style="color: #ffffff;">
      サブタイトル
    </p>
  </div>
  <p class="text-xl self-end" style="color: #ffffff;">
    発表者名
  </p>
</div>

---

<!-- _paginate: false -->

<style scoped>
section {
  background: linear-gradient(135deg, #1e3a8a, #0284c7, #06b6d4);
  color: #ffffff;
}
</style>

<div class="flex flex-col items-center justify-center h-full gap-4">
  <h1 class="text-5xl font-bold" style="color: #ffffff;">
    セクション名
  </h1>
</div>

---

<h2 class="text-4xl font-bold mb-8" style="color: #0284c7;">
  コンテンツの見出し
</h2>

<div class="text-xl leading-relaxed" style="color: #111827;">
  <p class="mb-4">
    ここに本文テキストが入ります。スライドの標準的なレイアウトで、見出しと本文テキストを組み合わせたコンテンツスライドです。
  </p>
  <p>
    複数の段落を使って、内容を分かりやすく伝えることができます。重要なポイントは<strong style="color: #0284c7;">強調表示</strong>で目立たせましょう。
  </p>
</div>

---

<h2 class="text-4xl font-bold mb-8" style="color: #0284c7;">
  2カラムレイアウト
</h2>

<div class="grid grid-cols-2 gap-8">
  <div class="p-6 rounded-lg" style="background-color: #f3f4f6;">
    <h3 class="text-xl font-bold mb-4" style="color: #0284c7;">左カラム</h3>
    <p class="text-sm" style="color: #111827;">
      左側のコンテンツをここに配置します。テキスト、画像、リストなど自由に使えます。
    </p>
  </div>
  <div class="p-6 rounded-lg" style="background-color: #f3f4f6;">
    <h3 class="text-xl font-bold mb-4" style="color: #0284c7;">右カラム</h3>
    <p class="text-sm" style="color: #111827;">
      右側のコンテンツをここに配置します。左右で対比や補足を表現できます。
    </p>
  </div>
</div>

---

<!-- _paginate: false -->

<style scoped>
section {
  background: linear-gradient(135deg, #1e3a8a, #0284c7, #06b6d4);
  color: #ffffff;
}
</style>

<div class="flex flex-col justify-center h-full gap-6">
  <h2 class="text-4xl font-bold" style="color: #ffffff;">
    まとめ
  </h2>
  <ul class="text-xl leading-loose list-disc pl-6" style="color: #ffffff;">
    <li>ポイント1：主要な結論や要点をここに</li>
    <li>ポイント2：次のステップやアクション</li>
    <li>ポイント3：補足情報やリソース</li>
  </ul>
</div>

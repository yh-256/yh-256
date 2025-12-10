<!-- Ultra-stylish GitHub Profile README -->

<!-- HERO: Gradient + Glitch + Signature -->
<div align="center">

  <!-- Gradient Banner with subtle noise & animated shimmer -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Hero">
    <defs>
      <linearGradient id="g" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#0f0c29"/>
        <stop offset="50%" stop-color="#302b63"/>
        <stop offset="100%" stop-color="#24243e"/>
      </linearGradient>
      <filter id="noise">
        <feTurbulence type="fractalNoise" baseFrequency="0.8" numOctaves="1" stitchTiles="stitch" />
        <feColorMatrix type="saturate" values="0"/>
        <feBlend mode="screen"/>
      </filter>
      <linearGradient id="shimmer" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="rgba(255,255,255,0)" />
        <stop offset="50%" stop-color="rgba(255,255,255,0.18)" />
        <stop offset="100%" stop-color="rgba(255,255,255,0)" />
      </linearGradient>
      <clipPath id="rounded">
        <rect x="0" y="0" width="1200" height="220" rx="22" ry="22"/>
      </clipPath>
      <filter id="glitch">
        <feColorMatrix type="matrix" values="
          1 0 0 0 0
          0 1 0 0 0
          0 0 1 0 0
          0 0 0 1 0"/>
      </filter>
    </defs>

    <rect width="1200" height="220" fill="url(#g)" clip-path="url(#rounded)"/>
    <rect width="1200" height="220" filter="url(#noise)" clip-path="url(#rounded)" opacity="0.05"/>

    <!-- Shimmer sweep -->
    <rect width="300" height="220" fill="url(#shimmer)" clip-path="url(#rounded)">
      <animate attributeName="x" from="-300" to="1200" dur="4s" repeatCount="indefinite"/>
    </rect>

    <!-- Signature Title -->
    <g filter="url(#glitch)">
      <text x="50%" y="52%" dominant-baseline="middle" text-anchor="middle"
            fill="#e2e8f0" font-size="42" font-weight="700" letter-spacing="1.2">
        Your Name / Software Engineer
      </text>

      <!-- subtle glitch layers -->
      <text x="50%" y="52%" dominant-baseline="middle" text-anchor="middle"
            fill="#7dd3fc" font-size="42" font-weight="700" opacity="0.35">
        <animate attributeName="dx" values="0;2;0;-1;0" dur="2s" repeatCount="indefinite"/>
        Your Name / Software Engineer
      </text>
      <text x="50%" y="52%" dominant-baseline="middle" text-anchor="middle"
            fill="#fca5a5" font-size="42" font-weight="700" opacity="0.25">
        <animate attributeName="dx" values="0;-2;0;1;0" dur="2s" repeatCount="indefinite"/>
        Your Name / Software Engineer
      </text>
    </g>

    <!-- tagline -->
    <text x="50%" y="78%" dominant-baseline="middle" text-anchor="middle"
          fill="#94a3b8" font-size="18" font-weight="500">
      Crafting delightful systems · AI / Cloud / DX · Minimal design believer
    </text>
  </svg>

</div>

<!-- NAV: quick links (icons via emoji for accessibility) -->
<p align="center">
  🚀 <b>Portfolio</b> · 🎓 <b>University</b> · 📝 <b>Blog</b> · 🎤 <b>Talks</b> · ✉️ <b>Contact</b>
</p>

---

## Highlights
- **Impact:** 使う人の体験が明確に良くなる技術選択と検証を徹底
- **Performance:** 設計時からレイテンシ/スループット/コストを三位一体で最適化
- **Craft:** テスト・CI・可観測性・運用をプロダクトの“機能”として扱う
- **Curiosity:** 研究→検証→発信のサイクルを常時回す

---

## Featured Work
<div align="center">

  <!-- Project cards: pure HTML so GitHub renders consistently -->
  <table>
    <tr>
      <td>
        <b>Project A</b><br/>
        AI×検索の高精度RAG。低レイテンシを実現する索引戦略とキャッシュ設計。<br/>
        Stack: Go / TypeScript / Vector Index / Observability
      </td>
      <td>
        <b>Project B</b><br/>
        Monorepo CIの高速化。依存グラフ活用で不要ビルドを削減、並列最適化。<br/>
        Stack: Node / Docker / Build system / Caching
      </td>
    </tr>
    <tr>
      <td>
        <b>Project C</b><br/>
        マルチテナントSaaS基盤。認可・監査ログ・テナント分離の原則設計。<br/>
        Stack: Auth / RBAC / SQL / Infra as Code
      </td>
      <td>
        <b>Project D</b><br/>
        開発者体験向上CLI。脚注レベルのUX改善で作業時間を短縮。<br/>
        Stack: CLI / DX / Packaging
      </td>
    </tr>
  </table>
</div>

---

## Skills
- **Languages:** Go / TypeScript / Python / Rust
- **Frameworks:** React / Next.js / FastAPI
- **Cloud/DevOps:** Containers / Orchestration / IaC / CI/CD
- **Data/AI:** SQL / Vector Index / Prompting / Evaluation
- **Ops:** Testing / Observability / Cost control

---

## Activity
- 📝 最新記事（自動更新枠）
- ⭐ 最近スターしたOSS（自動更新枠）
- 🎤 登壇/スライド（自動更新枠）

<!-- Dynamic blocks (Actionsで置換するマーカー) -->
<!-- BLOG START -->
- (auto)
<!-- BLOG END -->

<!-- STARS START -->
- (auto)
<!-- STARS END -->

---

## Thesis / Research
- **Theme:** 実運用に耐えるLLM×SaaSの設計指針
- **Focus:** 評価指標・安全性・スケーラビリティ・コスト最適化
- **Output:** 実験レポート・ベストプラクティス集・講演資料

---

## Contact
- 学術・インターン・共同研究のお話、歓迎です

<!-- Footer stripe -->
<div align="center">
  <svg width="100%" height="16" viewBox="0 0 1200 16" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="stripe" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#7dd3fc"/>
        <stop offset="50%" stop-color="#c084fc"/>
        <stop offset="100%" stop-color="#fca5a5"/>
      </linearGradient>
    </defs>
    <rect x="0" y="0" width="1200" height="16" fill="url(#stripe)" />
  </svg>
</div>

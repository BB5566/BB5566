<h1 align="center">Bob Tsou</h1>
<p align="center"><strong>前端工程師（Vue 3 × TypeScript）・地端 AI 內容產線負責人</strong></p>
<p align="center">
  <a href="https://bb-made.com/"><img src="https://img.shields.io/badge/作品集-bb--made.com-E4572E?style=flat-square" alt="作品集"></a>
  <a href="https://bb-made.com/resume.pdf"><img src="https://img.shields.io/badge/履歷-PDF-15161A?style=flat-square" alt="履歷 PDF"></a>
  <a href="https://bb-made.com/resume-en.pdf"><img src="https://img.shields.io/badge/Resume-English-15161A?style=flat-square" alt="English resume"></a>
</p>

---

<h3>關於我</h3>

- **團隊唯一前端**：負責教育平台前端主線（Vue 3 monorepo，串 .NET 8 API），台灣與中國兩套正式站，平台服務 2,100+ 所學校。
- **效能**：官網首頁讀取的資料約 2 MB→79 KB（本機量測）；打字測驗頁單頁少傳 2.4 MB。
- **地端 AI 內容產線**：2026/07 起一人重建與維運，模型推論全在公司內；改圖時間 66 秒→約 9 秒（測試量測）。
- **怎麼用 AI 寫程式**：以 AI coding 工具（Claude Code）為主力，前端與 AI 產線的規格、架構、測試與程式審查由我主導。
- **背景**：約 6 年電商設計與行銷，2025/10 轉前端；設計眼光和商業目標一起帶進工程。

<details>
  <summary>English</summary>

- **Sole frontend engineer** on an education platform (Vue 3 monorepo on a .NET 8 API), production sites in Taiwan and China, serving 2,100+ schools.
- **Performance**: cut the data the corporate homepage fetches from about 2 MB to 79 KB (local measurement); 2.4 MB less per typing-test page.
- **On-prem AI content pipeline**: rebuilt and run it on my own since July 2026, with all model inference inside the company; image-edit time 66 s → ~9 s (test measurement).
- **How I build with AI**: AI coding tools (Claude Code) do most of the typing; I own the specs, architecture, tests and code review for the frontend and the AI pipeline.
- **Background**: ~6 years in e-commerce design and marketing before moving to frontend in October 2025.

</details>

---

<h3 align="center">技能 / Skills</h3>
<table width="100%" align="center">
  <tr>
    <td align="center">
      <strong>Frontend</strong><br>
      <img src="https://skillicons.dev/icons?i=vue,nuxtjs,ts,js,vite,vitest,html,css,bootstrap" alt="frontend skills" />
    </td>
    <td align="center">
      <strong>Backend（AI 協作）</strong><br>
      <img src="https://skillicons.dev/icons?i=php,laravel,mysql" alt="backend skills" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Design</strong><br>
      <img src="https://skillicons.dev/icons?i=ps,ai,figma" alt="design skills" />
    </td>
    <td align="center">
      <strong>Tools</strong><br>
      <img src="https://skillicons.dev/icons?i=git,github,githubactions,gitlab,docker,vscode" alt="tools" />
    </td>
  </tr>
</table>

---

<h3>精選專案 / Featured Projects</h3>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>bb-made.com 作品集</h4>
      <p>「印刷打樣」風格的單頁作品集：精選作品照「問題→做法→結果」寫，附可親手操作的 AI 產線示範與壓縮前後對照；另有桌面作業系統風格的互動版 /os。內容正本以程式碼管理，合併 PR 即上線；Docker 自架在 NAS，經 Cloudflare Tunnel 對外，CI 跑 Lint、型別檢查、Vitest 與 Lighthouse（手機效能 89、無障礙 100）。</p>
      <p><code>Vue 3</code> <code>TypeScript</code> <code>GSAP</code> <code>Three.js</code> <code>Laravel 12</code> <code>Docker</code></p>
      <a href="https://bb-made.com/">網站</a> · <a href="https://github.com/BB5566/bb-portfolio">原始碼</a>
    </td>
    <td width="50%" valign="top">
      <h4>我怎麼審 AI 寫的程式</h4>
      <p>AI 說「完成了、測過了」不代表真的做了。動手前先訂紅線，寫完再過四道關：機器先擋、換一個模型審、看執行紀錄不看說法、數字上線前重量。這個作品集 AI 分支合併 59 個 PR（截至 2026/11/07），合併紀錄裡沒有退版。</p>
      <p><code>Claude Code</code> <code>GitHub Actions</code> <code>Vitest</code></p>
      <a href="https://bb-made.com/projects/27">看做法</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>stock-sync 多平台庫存同步</h4>
      <p>多個電商平台共用同一份庫存時，用「庫存帳本＋平台轉接器」處理併發扣減、限流重試與冪等；沒有平台 API 也能用 mock 平台完整驗證，每個設計決定都有測試。</p>
      <p><code>TypeScript</code> <code>Node.js</code> <code>SQLite</code> <code>node:test</code></p>
      <a href="https://github.com/BB5566/stock-sync">原始碼</a>
    </td>
    <td width="50%" valign="top">
      <h4>食在輔大</h4>
      <p>輔大心園餐廳介紹網站：店家、菜單與位置一頁看完，手機優先，已上線。</p>
      <p><code>React</code> <code>TypeScript</code> <code>Vite</code> <code>Cloudflare Workers</code></p>
      <a href="https://fju.bb-made.com/">網站</a> · <a href="https://github.com/BB5566/eat-at-fju">原始碼</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>MoodCanvas 心情日曆</h4>
      <p>輸入日記內容，系統用生成式 AI 產生符合情境的插畫與心情短語。</p>
      <p><code>PHP (MVC)</code> <code>SQLite</code> <code>JavaScript</code> <code>Replicate · FLUX Schnell</code></p>
      <a href="https://bb-made.com/mood/">網站</a> · <a href="https://github.com/BB5566/MoodCanvas">原始碼</a>
    </td>
    <td width="50%" valign="top">
      <h4>泰山投籃機（早期練習）</h4>
      <p>以夜市投籃機為靈感的網頁小遊戲，計時、計分與投籃動畫用原生 JavaScript 完成。</p>
      <p><code>HTML</code> <code>CSS</code> <code>JavaScript</code></p>
      <a href="https://bb5566.github.io/basketball-game/">試玩</a> · <a href="https://github.com/BB5566/basketball-game">原始碼</a>
    </td>
  </tr>
</table>

---

<h3>聯絡 / Contact</h3>

<a href="mailto:hello@bb-made.com">hello@bb-made.com</a> · <a href="https://bb-made.com/">bb-made.com</a>

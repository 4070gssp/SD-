<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#0a0604">
<title>すし大臣 50周年記念ルーレット</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@600;800&family=Noto+Serif+JP:wght@500;700;900&display=swap" rel="stylesheet">
<style>
  :root {
    --bg-deep: #0a0604;
    --bg-grad-1: #1a0f08;
    --bg-grad-2: #0a0604;
    --gold: #d4a851;
    --gold-bright: #f5d98a;
    --gold-deep: #8b6914;
    --red-ume: #8b1a1a;
    --cream: #f5ead0;
    --text: #f0e6cf;
    --text-dim: #a89878;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }

  html, body {
    width: 100%;
    min-height: 100vh;
    background: var(--bg-deep);
    font-family: "Noto Serif JP", "Shippori Mincho", serif;
    color: var(--text);
    overflow-x: hidden;
    user-select: none;
    -webkit-user-select: none;
  }

  body {
    background:
      radial-gradient(ellipse at top, #1f1208 0%, var(--bg-deep) 60%),
      var(--bg-deep);
    background-attachment: fixed;
    position: relative;
  }

  /* 和柄のテクスチャ背景 */
  body::before {
    content: "";
    position: fixed;
    inset: 0;
    background-image:
      radial-gradient(circle at 20% 30%, rgba(212, 168, 81, 0.04) 0%, transparent 40%),
      radial-gradient(circle at 80% 70%, rgba(139, 26, 26, 0.05) 0%, transparent 40%);
    pointer-events: none;
    z-index: 0;
  }

  /* 金箔の粒子 */
  body::after {
    content: "";
    position: fixed;
    inset: 0;
    background-image:
      radial-gradient(circle, rgba(245, 217, 138, 0.3) 1px, transparent 1px),
      radial-gradient(circle, rgba(212, 168, 81, 0.2) 1px, transparent 1px);
    background-size: 80px 80px, 120px 120px;
    background-position: 0 0, 40px 40px;
    opacity: 0.4;
    pointer-events: none;
    z-index: 0;
  }

  .app {
    position: relative;
    z-index: 1;
    max-width: 480px;
    margin: 0 auto;
    padding: 0 0 40px 0;
    min-height: 100vh;
  }

  /* ===== バナー ===== */
  .banner {
    width: 100%;
    display: block;
    border-bottom: 2px solid var(--gold-deep);
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
  }

  /* ===== タイトル ===== */
  .title-section {
    text-align: center;
    padding: 28px 20px 16px;
    position: relative;
  }

  .title-section::before,
  .title-section::after {
    content: "";
    position: absolute;
    top: 50%;
    width: 60px;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
  }
  .title-section::before { left: 8%; }
  .title-section::after { right: 8%; }

  .title-jp {
    font-family: "Shippori Mincho", serif;
    font-size: 22px;
    font-weight: 800;
    letter-spacing: 0.15em;
    color: var(--gold-bright);
    text-shadow:
      0 0 20px rgba(245, 217, 138, 0.4),
      0 2px 4px rgba(0, 0, 0, 0.8);
    margin-bottom: 6px;
  }

  .title-sub {
    font-size: 11px;
    letter-spacing: 0.3em;
    color: var(--text-dim);
    text-transform: uppercase;
  }

  /* ===== ルーレット枠 ===== */
  .roulette-frame {
    margin: 12px 16px 0;
    background: linear-gradient(180deg, #1a0f08 0%, #0f0805 100%);
    border: 2px solid var(--gold);
    border-radius: 18px;
    padding: 24px 14px;
    position: relative;
    box-shadow:
      0 0 0 4px var(--bg-deep),
      0 0 0 5px var(--gold-deep),
      0 12px 40px rgba(0, 0, 0, 0.6),
      inset 0 0 60px rgba(212, 168, 81, 0.08);
  }

  .roulette-frame::before {
    content: "";
    position: absolute;
    top: 8px; left: 8px; right: 8px; bottom: 8px;
    border: 1px solid rgba(212, 168, 81, 0.3);
    border-radius: 12px;
    pointer-events: none;
  }

  .reels-container {
    display: flex;
    gap: 8px;
    justify-content: center;
    padding: 8px 4px;
    position: relative;
  }

  /* リール表示窓 */
  .reel-window {
    flex: 1;
    aspect-ratio: 1 / 1;
    background: #000;
    border: 2px solid var(--gold);
    border-radius: 12px;
    overflow: hidden;
    position: relative;
    box-shadow:
      inset 0 6px 12px rgba(0, 0, 0, 0.9),
      inset 0 -6px 12px rgba(0, 0, 0, 0.9),
      0 0 14px rgba(212, 168, 81, 0.3);
  }

  /* リール内の画像ストリップ */
  .reel-strip {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    will-change: transform;
  }

  .reel-strip img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    display: block;
  }

  /* リール窓の光沢オーバーレイ */
  .reel-window::before {
    content: "";
    position: absolute;
    inset: 0;
    background:
      linear-gradient(180deg, rgba(0,0,0,0.5) 0%, transparent 20%, transparent 80%, rgba(0,0,0,0.5) 100%);
    pointer-events: none;
    z-index: 2;
  }

  /* 当選時の輝き */
  .reel-window.win::after {
    content: "";
    position: absolute;
    inset: -2px;
    border: 2px solid var(--gold-bright);
    border-radius: 12px;
    animation: winGlow 0.6s ease-in-out infinite alternate;
    pointer-events: none;
    z-index: 3;
  }

  @keyframes winGlow {
    from { box-shadow: 0 0 8px var(--gold-bright), inset 0 0 8px var(--gold-bright); }
    to   { box-shadow: 0 0 24px var(--gold-bright), inset 0 0 18px var(--gold-bright); }
  }

  /* ===== START ボタン ===== */
  .start-area {
    padding: 28px 20px 20px;
    text-align: center;
  }

  .start-btn {
    position: relative;
    display: inline-block;
    padding: 18px 56px;
    font-family: "Shippori Mincho", serif;
    font-size: 20px;
    font-weight: 800;
    letter-spacing: 0.4em;
    color: #1a0f08;
    background: linear-gradient(180deg, #f5d98a 0%, #d4a851 50%, #a07a30 100%);
    border: 2px solid var(--gold-bright);
    border-radius: 50px;
    cursor: pointer;
    box-shadow:
      0 0 0 2px var(--bg-deep),
      0 0 0 3px var(--gold-deep),
      0 8px 24px rgba(212, 168, 81, 0.4),
      inset 0 1px 0 rgba(255, 255, 255, 0.6);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
    text-shadow: 0 1px 0 rgba(255, 255, 255, 0.3);
  }

  .start-btn:active:not(:disabled) {
    transform: translateY(2px) scale(0.98);
    box-shadow:
      0 0 0 2px var(--bg-deep),
      0 0 0 3px var(--gold-deep),
      0 4px 12px rgba(212, 168, 81, 0.4),
      inset 0 1px 0 rgba(255, 255, 255, 0.6);
  }

  .start-btn:disabled {
    opacity: 0.5;
    cursor: not-allowed;
    background: linear-gradient(180deg, #6a5530 0%, #4a3a20 100%);
    color: var(--text-dim);
  }

  /* ボタンのキラリ */
  .start-btn::before {
    content: "";
    position: absolute;
    top: 0; left: -100%;
    width: 60%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.6), transparent);
    transform: skewX(-25deg);
    animation: shine 3s ease-in-out infinite;
    border-radius: 50px;
  }

  @keyframes shine {
    0%, 100% { left: -100%; }
    50% { left: 150%; }
  }

  .start-hint {
    margin-top: 14px;
    font-size: 12px;
    color: var(--text-dim);
    letter-spacing: 0.15em;
  }

  /* ===== ステータステキスト ===== */
  .status-text {
    text-align: center;
    padding: 0 20px 8px;
    min-height: 24px;
    font-size: 14px;
    letter-spacing: 0.1em;
    color: var(--gold-bright);
    font-family: "Shippori Mincho", serif;
    text-shadow: 0 0 12px rgba(245, 217, 138, 0.5);
  }

  /* ===== 賞品案内 ===== */
  .prize-list {
    margin: 24px 16px 0;
    padding: 18px 16px;
    background: rgba(26, 15, 8, 0.6);
    border: 1px solid rgba(212, 168, 81, 0.3);
    border-radius: 12px;
    backdrop-filter: blur(4px);
  }

  .prize-list-title {
    text-align: center;
    font-family: "Shippori Mincho", serif;
    font-size: 13px;
    letter-spacing: 0.4em;
    color: var(--gold);
    margin-bottom: 12px;
    padding-bottom: 8px;
    border-bottom: 1px solid rgba(212, 168, 81, 0.2);
  }

  /* 賞品アイテム */
  .prize-item {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 10px 0;
    border-bottom: 1px solid rgba(212, 168, 81, 0.1);
  }

  .prize-item:last-child {
    border-bottom: none;
  }

  .prize-item-sub {
    margin-top: 4px;
    padding-top: 12px;
    border-top: 1px dashed rgba(212, 168, 81, 0.25);
  }

  /* 3つ揃いのサムネイル */
  .prize-thumbs {
    display: flex;
    gap: 3px;
    flex-shrink: 0;
    padding: 4px;
    background: rgba(0, 0, 0, 0.4);
    border: 1px solid rgba(212, 168, 81, 0.4);
    border-radius: 6px;
    box-shadow:
      inset 0 1px 3px rgba(0, 0, 0, 0.5),
      0 0 8px rgba(212, 168, 81, 0.15);
  }

  .prize-thumb {
    width: 28px;
    height: 28px;
    border-radius: 4px;
    object-fit: cover;
    border: 1px solid rgba(212, 168, 81, 0.5);
    background: #000;
  }

  .prize-thumb-single {
    width: 90px;
    height: 28px;
    object-fit: cover;
    object-position: center;
  }

  /* 賞品情報 */
  .prize-info {
    flex: 1;
    display: flex;
    align-items: center;
    gap: 8px;
    flex-wrap: wrap;
    min-width: 0;
  }

  .prize-rank-badge {
    font-family: "Shippori Mincho", serif;
    font-weight: 800;
    font-size: 12px;
    padding: 2px 8px;
    border-radius: 4px;
    letter-spacing: 0.1em;
    flex-shrink: 0;
  }

  .prize-rank-1 {
    background: linear-gradient(135deg, #f5d98a 0%, #d4a851 100%);
    color: #2a1a0a;
    box-shadow: 0 0 6px rgba(245, 217, 138, 0.4);
  }

  .prize-rank-2 {
    background: linear-gradient(135deg, #d4d4d4 0%, #a8a8a8 100%);
    color: #2a1a0a;
  }

  .prize-rank-3 {
    background: linear-gradient(135deg, #d4a874 0%, #a07a4a 100%);
    color: #2a1a0a;
  }

  .prize-rank-sub {
    background: rgba(139, 105, 20, 0.3);
    color: var(--gold-bright);
    border: 1px solid rgba(212, 168, 81, 0.4);
    font-size: 10px;
  }

  .prize-name-text {
    color: var(--text);
    font-size: 13px;
    font-weight: 500;
    flex-shrink: 0;
  }

  .prize-desc-text {
    color: var(--text-dim);
    font-size: 11px;
    letter-spacing: 0.05em;
  }

  /* 小さい画面での調整 */
  @media (max-width: 380px) {
    .prize-thumb { width: 24px; height: 24px; }
    .prize-thumb-single { width: 78px; height: 24px; }
    .prize-name-text { font-size: 12px; }
    .prize-desc-text { font-size: 10px; }
    .prize-rank-badge { font-size: 11px; padding: 2px 6px; }
  }

  /* ===== クーポンオーバーレイ ===== */
  .coupon-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0, 0, 0, 0.85);
    backdrop-filter: blur(8px);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 100;
    padding: 20px;
    opacity: 0;
    transition: opacity 0.4s ease;
  }

  .coupon-overlay.show {
    display: flex;
    opacity: 1;
  }

  .coupon {
    background: linear-gradient(160deg, #f5ead0 0%, #e8d5a0 100%);
    color: #2a1a0a;
    width: 100%;
    max-width: 360px;
    border-radius: 20px;
    padding: 0;
    position: relative;
    box-shadow:
      0 20px 60px rgba(0, 0, 0, 0.8),
      0 0 0 4px var(--gold-deep),
      0 0 0 6px #f5d98a,
      0 0 80px rgba(245, 217, 138, 0.4);
    transform: scale(0.7) rotate(-3deg);
    opacity: 0;
    transition: transform 0.5s cubic-bezier(0.34, 1.56, 0.64, 1), opacity 0.4s ease;
    overflow: hidden;
  }

  .coupon-overlay.show .coupon {
    transform: scale(1) rotate(0deg);
    opacity: 1;
  }

  /* クーポンの和柄装飾 */
  .coupon::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
      radial-gradient(circle at 10% 10%, rgba(139, 26, 26, 0.08) 0%, transparent 30%),
      radial-gradient(circle at 90% 90%, rgba(212, 168, 81, 0.15) 0%, transparent 40%);
    pointer-events: none;
  }

  .coupon-top {
    background: linear-gradient(135deg, #8b1a1a 0%, #5a0e0e 100%);
    color: #f5ead0;
    padding: 18px 20px;
    text-align: center;
    position: relative;
    border-bottom: 3px solid var(--gold);
  }

  .coupon-top::after {
    content: "";
    position: absolute;
    bottom: -1px;
    left: 0; right: 0;
    height: 4px;
    background-image: radial-gradient(circle at 8px 4px, var(--bg-deep) 4px, transparent 4px);
    background-size: 16px 4px;
  }

  .coupon-grade {
    font-family: "Shippori Mincho", serif;
    font-size: 14px;
    letter-spacing: 0.5em;
    color: var(--gold-bright);
    margin-bottom: 4px;
  }

  .coupon-title-jp {
    font-family: "Shippori Mincho", serif;
    font-size: 24px;
    font-weight: 800;
    letter-spacing: 0.1em;
  }

  .coupon-body {
    padding: 24px 20px 20px;
    text-align: center;
    position: relative;
  }

  .coupon-prize-img {
    width: 130px;
    height: 130px;
    margin: 0 auto 12px;
    border-radius: 50%;
    border: 3px solid var(--gold);
    box-shadow:
      0 0 0 2px #f5ead0,
      0 0 30px rgba(212, 168, 81, 0.6);
    overflow: hidden;
  }

  .coupon-prize-img img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .coupon-prize-name {
    font-family: "Shippori Mincho", serif;
    font-size: 22px;
    font-weight: 800;
    color: #2a1a0a;
    margin-bottom: 6px;
    letter-spacing: 0.1em;
  }

  .coupon-discount {
    font-family: "Shippori Mincho", serif;
    font-size: 44px;
    font-weight: 800;
    color: #8b1a1a;
    line-height: 1;
    margin: 8px 0 4px;
    text-shadow: 1px 1px 0 rgba(212, 168, 81, 0.3);
  }

  .coupon-discount .pct { font-size: 28px; }
  .coupon-discount .label { font-size: 18px; font-weight: 600; }

  .coupon-desc {
    font-size: 13px;
    color: #5a3a1a;
    margin-top: 12px;
    line-height: 1.6;
    letter-spacing: 0.05em;
  }

  .coupon-bottom {
    padding: 0 20px 20px;
    position: relative;
  }

  .coupon-use-btn {
    width: 100%;
    padding: 16px;
    font-family: "Shippori Mincho", serif;
    font-size: 16px;
    font-weight: 700;
    letter-spacing: 0.3em;
    color: #f5ead0;
    background: linear-gradient(180deg, #3a2418 0%, #1a0f08 100%);
    border: 2px solid var(--gold);
    border-radius: 50px;
    cursor: pointer;
    box-shadow:
      0 4px 12px rgba(0, 0, 0, 0.3),
      inset 0 1px 0 rgba(245, 217, 138, 0.2);
    transition: all 0.2s ease;
  }

  .coupon-use-btn:active {
    transform: translateY(1px);
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.3);
  }

  .coupon-note {
    text-align: center;
    font-size: 10px;
    color: #8b6914;
    margin-top: 10px;
    letter-spacing: 0.1em;
  }

  /* 当選時の紙吹雪 */
  .confetti-container {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 99;
    overflow: hidden;
  }

  .confetti {
    position: absolute;
    width: 8px;
    height: 14px;
    top: -20px;
    animation: confettiFall linear forwards;
  }

  @keyframes confettiFall {
    to {
      transform: translateY(110vh) rotate(720deg);
    }
  }

  /* 当選時の演出オーバーレイ */
  .win-flash {
    position: fixed;
    inset: 0;
    background: radial-gradient(circle, rgba(245, 217, 138, 0.6) 0%, transparent 70%);
    pointer-events: none;
    z-index: 50;
    opacity: 0;
  }

  .win-flash.active {
    animation: flashAnim 0.8s ease-out;
  }

  @keyframes flashAnim {
    0% { opacity: 0; }
    20% { opacity: 1; }
    100% { opacity: 0; }
  }

  /* レスポンシブ調整 */
  @media (max-width: 400px) {
    .title-jp { font-size: 19px; }
    .start-btn { padding: 16px 42px; font-size: 18px; letter-spacing: 0.3em; }
    .roulette-frame { margin: 12px 12px 0; padding: 18px 10px; }
    .reels-container { gap: 6px; }
  }

  /* 桜の花びらの装飾 */
  .petal {
    position: fixed;
    color: rgba(245, 217, 138, 0.15);
    font-size: 20px;
    pointer-events: none;
    z-index: 0;
    animation: floatPetal 20s linear infinite;
  }

  @keyframes floatPetal {
    0% { transform: translateY(-50px) translateX(0) rotate(0deg); }
    100% { transform: translateY(110vh) translateX(50px) rotate(360deg); }
  }

  /* ===== パスワード入力モーダル ===== */
  .pw-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0, 0, 0, 0.92);
    backdrop-filter: blur(8px);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 250;
    padding: 20px;
  }
  .pw-overlay.show { display: flex; }

  .pw-panel {
    width: 100%;
    max-width: 300px;
    background: linear-gradient(180deg, #1f1208 0%, #120a05 100%);
    border: 2px solid var(--gold);
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0,0,0,0.9), 0 0 0 4px var(--bg-deep);
    padding-bottom: 20px;
  }

  .pw-header {
    text-align: center;
    padding: 22px 18px 6px;
    font-family: "Shippori Mincho", serif;
    font-size: 18px;
    font-weight: 800;
    letter-spacing: 0.4em;
    color: var(--gold-bright);
    border-bottom: 1px solid rgba(212,168,81,0.3);
  }

  .pw-sub {
    text-align: center;
    padding: 10px 18px 4px;
    font-size: 12px;
    color: var(--text-dim);
    letter-spacing: 0.1em;
  }

  /* 入力インジケーター（●） */
  .pw-dots {
    display: flex;
    justify-content: center;
    gap: 16px;
    padding: 18px 0 6px;
  }
  .pw-dot {
    width: 18px;
    height: 18px;
    border-radius: 50%;
    border: 2px solid rgba(212,168,81,0.5);
    background: transparent;
    transition: all 0.15s ease;
  }
  .pw-dot.filled {
    background: var(--gold-bright);
    border-color: var(--gold-bright);
    box-shadow: 0 0 8px rgba(245,217,138,0.6);
  }

  .pw-error {
    text-align: center;
    min-height: 20px;
    font-size: 12px;
    color: #e87070;
    padding: 4px 18px 0;
    letter-spacing: 0.05em;
  }

  /* テンキー */
  .pw-keys {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    padding: 12px 20px 0;
  }

  .pw-key {
    aspect-ratio: 1 / 1;
    border-radius: 50%;
    border: 1px solid rgba(212,168,81,0.4);
    background: rgba(255,255,255,0.04);
    color: var(--text);
    font-family: "Shippori Mincho", serif;
    font-size: 22px;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.1s ease;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .pw-key:active {
    background: rgba(212,168,81,0.25);
    border-color: var(--gold-bright);
    transform: scale(0.93);
  }
  .pw-key-cancel {
    background: rgba(139,26,26,0.2);
    border-color: rgba(139,26,26,0.6);
    color: #e87070;
    font-size: 18px;
  }
  .pw-key-del {
    background: rgba(212,168,81,0.08);
    color: var(--gold-bright);
    font-size: 18px;
  }

  /* ===== バナー設定パネル ===== */
  .banner-upload-btn {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    width: 100%;
    padding: 14px 0;
    border-radius: 12px;
    border: 2px dashed rgba(212,168,81,0.5);
    background: rgba(212,168,81,0.06);
    color: var(--gold-bright);
    font-size: 14px;
    font-family: "Shippori Mincho", serif;
    font-weight: 700;
    letter-spacing: 0.08em;
    cursor: pointer;
    transition: all 0.2s ease;
  }
  .banner-upload-btn:hover,
  .banner-upload-btn:active {
    background: rgba(212,168,81,0.15);
    border-color: var(--gold-bright);
  }

  /* ===== 管理画面 ===== */
  .admin-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0, 0, 0, 0.9);
    backdrop-filter: blur(6px);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 200;
    padding: 16px;
  }
  .admin-overlay.show { display: flex; }

  .admin-panel {
    width: 100%;
    max-width: 380px;
    background: linear-gradient(180deg, #1f1208 0%, #120a05 100%);
    border: 2px solid var(--gold);
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0,0,0,0.8), 0 0 0 4px var(--bg-deep);
  }

  .admin-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 18px;
    background: linear-gradient(135deg, #8b1a1a 0%, #5a0e0e 100%);
    border-bottom: 2px solid var(--gold);
    font-family: "Shippori Mincho", serif;
    font-size: 16px;
    font-weight: 800;
    color: var(--gold-bright);
    letter-spacing: 0.1em;
  }
  .admin-close {
    background: none;
    border: none;
    color: var(--gold-bright);
    font-size: 28px;
    line-height: 1;
    cursor: pointer;
    padding: 0 4px;
  }

  .admin-tabs {
    display: flex;
    gap: 0;
    border-bottom: 1px solid rgba(212,168,81,0.3);
  }
  .admin-tab {
    flex: 1;
    padding: 12px;
    background: transparent;
    border: none;
    border-bottom: 3px solid transparent;
    color: var(--text-dim);
    font-family: "Shippori Mincho", serif;
    font-size: 14px;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.2s;
  }
  .admin-tab.active {
    color: var(--gold-bright);
    border-bottom-color: var(--gold);
    background: rgba(212,168,81,0.08);
  }

  .admin-date {
    text-align: center;
    padding: 10px;
    font-size: 13px;
    color: var(--gold);
    letter-spacing: 0.1em;
  }

  .admin-table {
    width: 100%;
    border-collapse: collapse;
    margin: 0 0 8px;
  }
  .admin-table th {
    background: rgba(212,168,81,0.15);
    color: var(--gold-bright);
    font-size: 12px;
    padding: 8px 18px;
    text-align: left;
    font-weight: 700;
  }
  .admin-table th:last-child { text-align: right; }
  .admin-table td {
    padding: 11px 18px;
    font-size: 14px;
    color: var(--text);
    border-bottom: 1px solid rgba(212,168,81,0.12);
  }
  .admin-table td:last-child {
    text-align: right;
    font-weight: 800;
    font-size: 18px;
    color: var(--gold-bright);
    font-family: "Shippori Mincho", serif;
  }
  .admin-total-row td {
    background: rgba(26,15,8,0.6);
    border-top: 2px solid var(--gold);
    font-weight: 800;
  }
  .admin-total-row td:last-child { color: #fff; }

  .dot {
    display: inline-block;
    width: 10px; height: 10px;
    border-radius: 50%;
    margin-right: 8px;
    vertical-align: middle;
  }
  .dot-1 { background: linear-gradient(135deg,#f5d98a,#d4a851); }
  .dot-2 { background: linear-gradient(135deg,#d4d4d4,#a8a8a8); }
  .dot-3 { background: linear-gradient(135deg,#d4a874,#a07a4a); }
  .dot-sub { background: rgba(139,105,20,0.6); border:1px solid var(--gold); }

  .admin-actions {
    display: flex;
    flex-direction: column;
    gap: 8px;
    padding: 14px 18px 4px;
  }
  .admin-btn {
    padding: 12px;
    border-radius: 8px;
    font-family: "Shippori Mincho", serif;
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 0.1em;
    cursor: pointer;
    border: 1px solid var(--gold);
    transition: all 0.15s;
  }
  .admin-btn:active { transform: translateY(1px); }
  .admin-btn-copy {
    background: linear-gradient(180deg,#f5d98a,#d4a851);
    color: #1a0f08;
  }
  .admin-btn-csv {
    background: rgba(212,168,81,0.12);
    color: var(--gold-bright);
  }
  .admin-btn-reset {
    background: rgba(139,26,26,0.2);
    color: #e8a0a0;
    border-color: #8b1a1a;
  }

  .admin-note {
    text-align: center;
    min-height: 18px;
    padding: 6px 18px 0;
    font-size: 12px;
    color: #7ec77e;
  }
  .admin-foot {
    padding: 8px 18px 16px;
    font-size: 10px;
    color: var(--text-dim);
    text-align: center;
    line-height: 1.5;
  }

  /* 確率設定パネル */
  .prob-desc {
    padding: 12px 18px 8px;
    font-size: 12px;
    color: var(--text-dim);
    line-height: 1.6;
    text-align: center;
  }
  .prob-table {
    width: 100%;
    border-collapse: collapse;
    margin: 0 0 4px;
  }
  .prob-table th {
    background: rgba(212,168,81,0.15);
    color: var(--gold-bright);
    font-size: 12px;
    padding: 8px 18px;
    text-align: left;
    font-weight: 700;
  }
  .prob-table th:last-child { text-align: center; }
  .prob-table td {
    padding: 8px 18px;
    font-size: 14px;
    color: var(--text);
    border-bottom: 1px solid rgba(212,168,81,0.12);
  }
  .prob-table td:last-child { text-align: center; }
  .prob-input {
    width: 72px;
    padding: 7px 10px;
    background: rgba(0,0,0,0.5);
    border: 1px solid var(--gold);
    border-radius: 6px;
    color: var(--gold-bright);
    font-family: "Shippori Mincho", serif;
    font-size: 16px;
    font-weight: 700;
    text-align: center;
    -moz-appearance: textfield;
  }
  .prob-input:focus {
    outline: none;
    border-color: var(--gold-bright);
    box-shadow: 0 0 8px rgba(245,217,138,0.4);
  }
  .prob-input::-webkit-inner-spin-button,
  .prob-input::-webkit-outer-spin-button { -webkit-appearance: none; }
  .prob-rest {
    color: var(--text-dim);
    font-size: 15px;
    font-weight: 700;
  }
  .prob-total-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 18px;
    background: rgba(26,15,8,0.6);
    border-top: 2px solid var(--gold);
    border-bottom: 1px solid rgba(212,168,81,0.2);
    font-family: "Shippori Mincho", serif;
    font-size: 14px;
    font-weight: 700;
    color: var(--text);
  }
  .prob-total-val {
    font-size: 20px;
    font-weight: 800;
    color: var(--gold-bright);
    transition: color 0.2s;
  }
  .prob-total-val.over { color: #e87070; }
  .prob-total-val.ok   { color: #7ec77e; }

  /* 商品設定パネル */
  .prize-edit-wrap {
    padding: 4px 18px 0;
  }
  .prize-edit-block {
    margin-bottom: 14px;
    padding: 10px 12px;
    background: rgba(0,0,0,0.25);
    border: 1px solid rgba(212,168,81,0.25);
    border-radius: 8px;
  }
  .prize-edit-head {
    font-family: "Shippori Mincho", serif;
    font-weight: 800;
    font-size: 14px;
    color: var(--gold-bright);
    margin-bottom: 8px;
  }
  .prize-edit-row {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-bottom: 6px;
  }
  .prize-edit-row span {
    flex: 0 0 64px;
    font-size: 12px;
    color: var(--text-dim);
  }
  .prize-input {
    flex: 1;
    min-width: 0;
    padding: 7px 10px;
    background: rgba(0,0,0,0.5);
    border: 1px solid var(--gold);
    border-radius: 6px;
    color: var(--gold-bright);
    font-family: "Shippori Mincho", serif;
    font-size: 14px;
    -moz-appearance: textfield;
  }
  .prize-input:focus {
    outline: none;
    border-color: var(--gold-bright);
    box-shadow: 0 0 8px rgba(245,217,138,0.4);
  }
  .prize-input-num { flex: 0 0 80px; text-align: center; font-weight: 700; }
  .prize-input::-webkit-inner-spin-button,
  .prize-input::-webkit-outer-spin-button { -webkit-appearance: none; }
  .prize-edit-note {
    font-size: 10px;
    color: var(--text-dim);
    margin-top: 4px;
  }
</style>
</head>
<body>
  <div class="app">
    <img class="banner" src="data:image/jpeg;base64,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" alt="すし大臣 50周年記念ルーレット企画 お会計最大20%引き">

    <div class="title-section">
      <div class="title-jp">50周年感謝イベント抽選</div>
      <div class="title-sub">SUSHI ROULETTE</div>
    </div>

    <div class="roulette-frame">
      <div class="reels-container">
        <div class="reel-window" id="reel0">
          <div class="reel-strip" id="strip0"></div>
        </div>
        <div class="reel-window" id="reel1">
          <div class="reel-strip" id="strip1"></div>
        </div>
        <div class="reel-window" id="reel2">
          <div class="reel-strip" id="strip2"></div>
        </div>
      </div>
    </div>

    <div class="start-area">
      <div class="status-text" id="statusText">ボタンを押して抽選開始</div>
      <button class="start-btn" id="startBtn">抽 選 開 始</button>
      <div class="start-hint">※ お会計時のみご利用いただけます</div>
    </div>

    <div class="prize-list">
      <div class="prize-list-title">― 賞品一覧 ―</div>

      <div class="prize-item prize-item-1">
        <div class="prize-thumbs">
          <img class="prize-thumb" id="thumbTuna1" src="" alt="マグロ">
          <img class="prize-thumb" id="thumbTuna2" src="" alt="マグロ">
          <img class="prize-thumb" id="thumbTuna3" src="" alt="マグロ">
        </div>
        <div class="prize-info">
          <span class="prize-rank-badge prize-rank-1">一等</span>
          <span class="prize-name-text" id="listNameTuna">マグロ鮨 揃い</span>
          <span class="prize-desc-text" id="listDescTuna">20%引きクーポン</span>
        </div>
      </div>

      <div class="prize-item prize-item-2">
        <div class="prize-thumbs">
          <img class="prize-thumb" id="thumbSalmon1" src="" alt="サーモン">
          <img class="prize-thumb" id="thumbSalmon2" src="" alt="サーモン">
          <img class="prize-thumb" id="thumbSalmon3" src="" alt="サーモン">
        </div>
        <div class="prize-info">
          <span class="prize-rank-badge prize-rank-2">二等</span>
          <span class="prize-name-text" id="listNameSalmon">サーモン寿司 揃い</span>
          <span class="prize-desc-text" id="listDescSalmon">10%引きクーポン</span>
        </div>
      </div>

      <div class="prize-item prize-item-3">
        <div class="prize-thumbs">
          <img class="prize-thumb" id="thumbTamago1" src="" alt="玉子">
          <img class="prize-thumb" id="thumbTamago2" src="" alt="玉子">
          <img class="prize-thumb" id="thumbTamago3" src="" alt="玉子">
        </div>
        <div class="prize-info">
          <span class="prize-rank-badge prize-rank-3">三等</span>
          <span class="prize-name-text" id="listNameTamago">玉子寿司 揃い</span>
          <span class="prize-desc-text" id="listDescTamago">5%引きクーポン</span>
        </div>
      </div>

      <div class="prize-item prize-item-sub">
        <div class="prize-thumbs">
          <img class="prize-thumb prize-thumb-single" id="thumbDrink" src="" alt="ワンドリンク">
        </div>
        <div class="prize-info">
          <span class="prize-rank-badge prize-rank-sub">参加賞</span>
          <span class="prize-name-text" id="listNameDrink">ワンドリンク無料</span>
          <span class="prize-desc-text">次回ご来店時</span>
        </div>
      </div>
    </div>
  </div>

  <!-- 当選フラッシュ -->
  <div class="win-flash" id="winFlash"></div>

  <!-- クーポンオーバーレイ -->
  <div class="coupon-overlay" id="couponOverlay">
    <div class="coupon" id="coupon">
      <div class="coupon-top">
        <div class="coupon-grade" id="couponGrade">参 加 賞</div>
        <div class="coupon-title-jp" id="couponTitle">ご来店ありがとうございます</div>
      </div>
      <div class="coupon-body">
        <div class="coupon-prize-img" id="couponImg">
          <img id="couponImgSrc" src="" alt="">
        </div>
        <div class="coupon-prize-name" id="couponPrizeName">ワンドリンク無料</div>
        <div class="coupon-discount" id="couponDiscount">
          <span class="label">次回使える</span>
        </div>
        <div class="coupon-desc" id="couponDesc">次回ご来店時に1ドリンク無料サービス</div>
      </div>
      <div class="coupon-bottom">
        <button class="coupon-use-btn" id="couponUseBtn">利 用 済 み</button>
        <div class="coupon-note">※ スタッフにこの画面をお見せください</div>
      </div>
    </div>
  </div>

  <!-- 紙吹雪コンテナ -->
  <div class="confetti-container" id="confettiContainer"></div>

  <!-- パスワード入力モーダル -->
  <div class="pw-overlay" id="pwOverlay">
    <div class="pw-panel">
      <div class="pw-header">管 理 画 面</div>
      <div class="pw-sub">パスワードを入力してください</div>
      <div class="pw-dots" id="pwDots">
        <span class="pw-dot" id="dot0"></span>
        <span class="pw-dot" id="dot1"></span>
        <span class="pw-dot" id="dot2"></span>
        <span class="pw-dot" id="dot3"></span>
      </div>
      <div class="pw-error" id="pwError"></div>
      <div class="pw-keys">
        <button class="pw-key" data-n="1">1</button>
        <button class="pw-key" data-n="2">2</button>
        <button class="pw-key" data-n="3">3</button>
        <button class="pw-key" data-n="4">4</button>
        <button class="pw-key" data-n="5">5</button>
        <button class="pw-key" data-n="6">6</button>
        <button class="pw-key" data-n="7">7</button>
        <button class="pw-key" data-n="8">8</button>
        <button class="pw-key" data-n="9">9</button>
        <button class="pw-key pw-key-cancel" id="pwCancel">✕</button>
        <button class="pw-key" data-n="0">0</button>
        <button class="pw-key pw-key-del" id="pwDel">⌫</button>
      </div>
    </div>
  </div>

  <!-- 隠し管理画面（タイトルを5回タップで開く） -->
  <div class="admin-overlay" id="adminOverlay">
    <div class="admin-panel">
      <div class="admin-header">
        <span>当選本数 管理画面</span>
        <button class="admin-close" id="adminClose">×</button>
      </div>

      <div class="admin-tabs">
        <button class="admin-tab active" id="tabToday">本日分</button>
        <button class="admin-tab" id="tabTotal">累計</button>
        <button class="admin-tab" id="tabProb">確率設定</button>
        <button class="admin-tab" id="tabPrize">商品設定</button>
        <button class="admin-tab" id="tabPw">PW設定</button>
        <button class="admin-tab" id="tabBanner">バナー</button>
      </div>

      <!-- 集計パネル -->
      <div id="panelCount">
        <div class="admin-date" id="adminDate"></div>
        <table class="admin-table">
          <thead>
            <tr><th>賞</th><th>本数</th></tr>
          </thead>
          <tbody>
            <tr><td><span class="dot dot-1"></span>1等 マグロ (20%引)</td><td id="cntTuna">0</td></tr>
            <tr><td><span class="dot dot-2"></span>2等 サーモン (10%引)</td><td id="cntSalmon">0</td></tr>
            <tr><td><span class="dot dot-3"></span>3等 玉子 (5%引)</td><td id="cntTamago">0</td></tr>
            <tr><td><span class="dot dot-sub"></span>参加賞 ドリンク</td><td id="cntDrink">0</td></tr>
            <tr class="admin-total-row"><td>抽選回数 合計</td><td id="cntTotal">0</td></tr>
          </tbody>
        </table>
        <div class="admin-actions">
          <button class="admin-btn admin-btn-copy" id="btnCopy">本日分をコピー</button>
          <button class="admin-btn admin-btn-csv" id="btnCsv">全履歴CSV保存</button>
          <button class="admin-btn admin-btn-reset" id="btnReset">本日分をリセット</button>
        </div>
        <div class="admin-note" id="adminMsg"></div>
        <div class="admin-foot">※ この画面はお客様には表示されません。スプレッドシートに転記後、本日分リセットでクリアできます。</div>
      </div>

      <!-- 確率設定パネル -->
      <div id="panelProb" style="display:none;">
        <div class="prob-desc">各等級の当選確率を設定します。<br>合計が100%になるように入力してください。</div>
        <table class="prob-table">
          <thead>
            <tr><th>賞</th><th>確率（%）</th></tr>
          </thead>
          <tbody>
            <tr>
              <td><span class="dot dot-1"></span>1等 マグロ</td>
              <td><input class="prob-input" id="probTuna" type="number" min="0" max="100" step="0.1" value="1"></td>
            </tr>
            <tr>
              <td><span class="dot dot-2"></span>2等 サーモン</td>
              <td><input class="prob-input" id="probSalmon" type="number" min="0" max="100" step="0.1" value="3"></td>
            </tr>
            <tr>
              <td><span class="dot dot-3"></span>3等 玉子</td>
              <td><input class="prob-input" id="probTamago" type="number" min="0" max="100" step="0.1" value="5"></td>
            </tr>
            <tr class="admin-total-row">
              <td>参加賞（自動）</td>
              <td class="prob-rest" id="probDrinkRest">91%</td>
            </tr>
          </tbody>
        </table>
        <div class="prob-total-row">
          <span>合計</span>
          <span id="probTotal" class="prob-total-val">100%</span>
        </div>
        <div class="admin-actions">
          <button class="admin-btn admin-btn-copy" id="btnProbSave">確率を保存して適用</button>
          <button class="admin-btn admin-btn-reset" id="btnProbReset">デフォルトに戻す</button>
        </div>
        <div class="admin-note" id="probMsg"></div>
        <div class="admin-foot">※ 参加賞の確率は自動計算されます。<br>保存後すぐに次の抽選から新しい確率が適用されます。</div>
      </div>

      <!-- 商品設定パネル -->
      <div id="panelPrize" style="display:none;">
        <div class="prob-desc">各賞の商品名・割引率・説明文を変更できます。<br>変更後すぐにクーポン表示と賞品一覧へ反映されます。</div>
        <div class="prize-edit-wrap">
          <div class="prize-edit-block">
            <div class="prize-edit-head"><span class="dot dot-1"></span>1等</div>
            <label class="prize-edit-row"><span>商品名</span><input class="prize-input" id="pnTuna" type="text"></label>
            <label class="prize-edit-row"><span>割引率(%)</span><input class="prize-input prize-input-num" id="pdTuna" type="number" min="0" max="100" step="1"></label>
            <label class="prize-edit-row"><span>説明文</span><input class="prize-input" id="peTuna" type="text"></label>
          </div>
          <div class="prize-edit-block">
            <div class="prize-edit-head"><span class="dot dot-2"></span>2等</div>
            <label class="prize-edit-row"><span>商品名</span><input class="prize-input" id="pnSalmon" type="text"></label>
            <label class="prize-edit-row"><span>割引率(%)</span><input class="prize-input prize-input-num" id="pdSalmon" type="number" min="0" max="100" step="1"></label>
            <label class="prize-edit-row"><span>説明文</span><input class="prize-input" id="peSalmon" type="text"></label>
          </div>
          <div class="prize-edit-block">
            <div class="prize-edit-head"><span class="dot dot-3"></span>3等</div>
            <label class="prize-edit-row"><span>商品名</span><input class="prize-input" id="pnTamago" type="text"></label>
            <label class="prize-edit-row"><span>割引率(%)</span><input class="prize-input prize-input-num" id="pdTamago" type="number" min="0" max="100" step="1"></label>
            <label class="prize-edit-row"><span>説明文</span><input class="prize-input" id="peTamago" type="text"></label>
          </div>
          <div class="prize-edit-block">
            <div class="prize-edit-head"><span class="dot dot-sub"></span>参加賞</div>
            <label class="prize-edit-row"><span>商品名</span><input class="prize-input" id="pnDrink" type="text"></label>
            <label class="prize-edit-row"><span>説明文</span><input class="prize-input" id="peDrink" type="text"></label>
            <div class="prize-edit-note">※ 参加賞は割引率ではなく「FREE」表示になります</div>
          </div>
        </div>
        <div class="admin-actions">
          <button class="admin-btn admin-btn-copy" id="btnPrizeSave">商品を保存して適用</button>
          <button class="admin-btn admin-btn-reset" id="btnPrizeReset">デフォルトに戻す</button>
        </div>
        <div class="admin-note" id="prizeMsg"></div>
        <div class="admin-foot">※ アイコン画像の変更はできません（文言・割引率のみ）。</div>
      </div>

      <!-- PW設定パネル -->
      <div id="panelPw" style="display:none;">
        <div class="prob-desc">管理画面に入るためのパスワードを変更します。<br>4桁の数字で設定してください。</div>
        <div style="padding: 14px 18px 0;">
          <label class="prize-edit-row" style="margin-bottom:10px;">
            <span style="flex:0 0 84px; font-size:12px; color:var(--text-dim);">現在のPW</span>
            <input class="prize-input prize-input-num" id="pwCurrent" type="password" maxlength="4" inputmode="numeric" placeholder="****">
          </label>
          <label class="prize-edit-row" style="margin-bottom:10px;">
            <span style="flex:0 0 84px; font-size:12px; color:var(--text-dim);">新しいPW</span>
            <input class="prize-input prize-input-num" id="pwNew" type="password" maxlength="4" inputmode="numeric" placeholder="****">
          </label>
          <label class="prize-edit-row" style="margin-bottom:4px;">
            <span style="flex:0 0 84px; font-size:12px; color:var(--text-dim);">確認</span>
            <input class="prize-input prize-input-num" id="pwConfirm" type="password" maxlength="4" inputmode="numeric" placeholder="****">
          </label>
        </div>
        <div class="admin-actions">
          <button class="admin-btn admin-btn-copy" id="btnPwSave">パスワードを変更</button>
          <button class="admin-btn admin-btn-reset" id="btnPwReset">デフォルト(1234)に戻す</button>
        </div>
        <div class="admin-note" id="pwChangeMsg"></div>
        <div class="admin-foot">※ 初期パスワードは <strong style="color:var(--gold)">1234</strong> です。</div>
      </div>

      <!-- バナー設定パネル -->
      <div id="panelBanner" style="display:none;">
        <div class="prob-desc">トップに表示するバナー画像を差し替えます。</div>
        <div style="padding: 14px 18px 0;">
          <!-- 現在のバナープレビュー -->
          <div style="margin-bottom:12px;">
            <div style="font-size:11px; color:var(--text-dim); margin-bottom:6px; letter-spacing:0.05em;">現在のバナー</div>
            <img id="bannerPreview" style="width:100%; border-radius:8px; border:1px solid rgba(212,168,81,0.3);" alt="現在のバナー">
          </div>
          <!-- アップロードボタン -->
          <label class="banner-upload-btn" for="bannerFileInput">
            <span>📁 端末から画像を選択</span>
            <input type="file" id="bannerFileInput" accept="image/*" style="display:none;">
          </label>
          <!-- 新バナープレビュー -->
          <div id="newBannerWrap" style="display:none; margin-top:12px;">
            <div style="font-size:11px; color:var(--text-dim); margin-bottom:6px; letter-spacing:0.05em;">新しいバナー（プレビュー）</div>
            <img id="newBannerPreview" style="width:100%; border-radius:8px; border:1px solid rgba(212,168,81,0.5);" alt="新しいバナー">
          </div>
        </div>
        <div class="admin-actions" style="margin-top:10px;">
          <button class="admin-btn admin-btn-copy" id="btnBannerSave" disabled>バナーを更新</button>
          <button class="admin-btn admin-btn-reset" id="btnBannerReset">デフォルトに戻す</button>
        </div>
        <div class="admin-note" id="bannerMsg"></div>
        <div class="admin-foot">
          ※ 推奨サイズ: <strong style="color:var(--gold)">1024 × 413 px</strong>（横長）<br>
          ※ 形式: JPEG / PNG（容量 2MB 以下推奨）<br>
          ※ 設定はこの端末のみに保存されます。
        </div>
      </div>
    </div>
  </div>

<script>
(function() {
  'use strict';

  // ===== 画像データ（Base64） =====
  const IMG = {
    tuna:   'data:image/jpeg;base64,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Fbqv/Gll/wA4Mv8A8Cn8K3Vf+NLL/nBl/wDgVrjpWs/4Swr+n+7/ANllf5rVc/p+iz91H4ndT5HCRRz5fDR28c4kla81DcZfYcWUcIFWIlt2Hvcuy8ux+Fucr4gsrPj08rVtna+XIGcYbTzpcSjYjiGunkjA3IY+7v7uwPfviRSsqLZnDIrfD8gf7gT81adiVS7j36WV8871kusz5kN9dZ7O2s1uYZlny3sCOh3DRtDahY3BBO7MCx32PYCqBm17mxjjaYyKywFu3LzExtqIuZYAb7ncggDsV2P7BtRVK3sWG0ULd1rBblw9tPYLBdUTPNyVHubm5vLx7m7uJLq4fbnLM5dm2Gw3J7nsAKgUpW0AAFgsZKUpVUSlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURKUpREpSlESlKURf/9k=',
    salmon: 'data:image/jpeg;base64,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',
    tamago: 'data:image/jpeg;base64,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'
  };
  // IMGオブジェクトにバナー初期srcを保存（デフォルト復元用）
  IMG.banner = document.querySelector('.banner') ? document.querySelector('.banner').src : '';


  // ===== 賞品定義 =====
  // 確率: 1等1%, 2等3%, 3等5%, 参加賞91%
  const SYMBOLS = ['tuna', 'salmon', 'tamago'];
  const PRIZES = {
    tuna: {
      grade: '一 等 当 選',
      title: 'おめでとうございます',
      prizeName: 'マグロ鮨 揃い',
      discount: '20',
      desc: 'お会計より20%割引いたします',
      img: IMG.tuna,
      color: '#8b1a1a'
    },
    salmon: {
      grade: '二 等 当 選',
      title: 'おめでとうございます',
      prizeName: 'サーモン寿司 揃い',
      discount: '10',
      desc: 'お会計より10%割引いたします',
      img: IMG.salmon,
      color: '#c44a1a'
    },
    tamago: {
      grade: '三 等 当 選',
      title: 'おめでとうございます',
      prizeName: '玉子寿司 揃い',
      discount: '5',
      desc: 'お会計より5%割引いたします',
      img: IMG.tamago,
      color: '#c49a1a'
    },
    drink: {
      grade: '参 加 賞',
      title: 'ご来店ありがとうございます',
      prizeName: 'ワンドリンク無料',
      discount: null,
      desc: '次回ご来店時に1ドリンク無料サービス',
      img: 'data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzNDAgMzM1IiB3aWR0aD0iMzQwIiBoZWlnaHQ9IjMzNSI+CiAgPGRlZnM+CiAgICA8IS0tIOiDjOaZr+OBruWSjOafhOOCsOODqeODh+ODvOOCt+ODp+ODsyAtLT4KICAgIDxyYWRpYWxHcmFkaWVudCBpZD0iYmdHcmFkIiBjeD0iNTAlIiBjeT0iNTAlIiByPSI1MCUiPgogICAgICA8c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSIjM2EyNDE4Ii8+CiAgICAgIDxzdG9wIG9mZnNldD0iNjAlIiBzdG9wLWNvbG9yPSIjMWEwZjA4Ii8+CiAgICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0iIzBhMDYwNCIvPgogICAgPC9yYWRpYWxHcmFkaWVudD4KICAgIDwhLS0g6YeR6Imy44Kw44Op44OH44O844K344On44Oz77yI44Oh44OA44Or5p6g55So77yJIC0tPgogICAgPGxpbmVhckdyYWRpZW50IGlkPSJnb2xkRnJhbWUiIHgxPSIwJSIgeTE9IjAlIiB4Mj0iMCUiIHkyPSIxMDAlIj4KICAgICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2Y1ZDk4YSIvPgogICAgICA8c3RvcCBvZmZzZXQ9IjUwJSIgc3RvcC1jb2xvcj0iI2Q0YTg1MSIvPgogICAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiM4YjY5MTQiLz4KICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICA8IS0tIOODoeODgOODq+WGhemDqOOBruWFiSAtLT4KICAgIDxyYWRpYWxHcmFkaWVudCBpZD0ibWVkYWxHbG93IiBjeD0iNTAlIiBjeT0iNDAlIiByPSI2MCUiPgogICAgICA8c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSJyZ2JhKDI0NSwyMTcsMTM4LDAuMykiLz4KICAgICAgPHN0b3Agb2Zmc2V0PSI3MCUiIHN0b3AtY29sb3I9InJnYmEoMjEyLDE2OCw4MSwwLjEpIi8+CiAgICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0icmdiYSgwLDAsMCwwLjQpIi8+CiAgICA8L3JhZGlhbEdyYWRpZW50PgogICAgPCEtLSDjg5Pjg7zjg6vjga7mtrLkvZPjgrDjg6njg4fjg7zjgrfjg6fjg7MgLS0+CiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImJlZXJMaXF1aWQiIHgxPSIwJSIgeTE9IjAlIiB4Mj0iMCUiIHkyPSIxMDAlIj4KICAgICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2Y1YzU0MiIvPgogICAgICA8c3RvcCBvZmZzZXQ9IjUwJSIgc3RvcC1jb2xvcj0iI2U4YTgyMCIvPgogICAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiNiODgzMGYiLz4KICAgIDwvbGluZWFyR3JhZGllbnQ+CiAgICA8IS0tIOOCuOODp+ODg+OCreOBruOCrOODqeOCuSAtLT4KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0iZ2xhc3NHcmFkIiB4MT0iMCUiIHkxPSIwJSIgeDI9IjEwMCUiIHkyPSIwJSI+CiAgICAgIDxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9InJnYmEoMjU1LDI1NSwyNTUsMC40KSIvPgogICAgICA8c3RvcCBvZmZzZXQ9IjUwJSIgc3RvcC1jb2xvcj0icmdiYSgyNTUsMjU1LDI1NSwwLjEpIi8+CiAgICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0icmdiYSgyNTUsMjU1LDI1NSwwLjMpIi8+CiAgICA8L2xpbmVhckdyYWRpZW50PgogICAgPCEtLSDms6EgLS0+CiAgICA8cmFkaWFsR3JhZGllbnQgaWQ9ImZvYW1HcmFkIiBjeD0iNTAlIiBjeT0iNDAlIiByPSI2MCUiPgogICAgICA8c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSIjZmZmZmZmIi8+CiAgICAgIDxzdG9wIG9mZnNldD0iNjAlIiBzdG9wLWNvbG9yPSIjZjVlYWQwIi8+CiAgICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0iI2Q0YzVhMCIvPgogICAgPC9yYWRpYWxHcmFkaWVudD4KICA8L2RlZnM+CgogIDwhLS0g6IOM5pmvIC0tPgogIDxyZWN0IHdpZHRoPSIzNDAiIGhlaWdodD0iMzM1IiBmaWxsPSJ1cmwoI2JnR3JhZCkiLz4KCiAgPCEtLSDlkozmn4Tjga7oo4Xpo77lhobvvIjlpJblgbTjga7jgbzjgpPjgoTjgorjgZfjgZ/ph5HoibLjga7ovJ3jgY3vvIkgLS0+CiAgPGNpcmNsZSBjeD0iMTcwIiBjeT0iMTY3IiByPSIxNTUiIGZpbGw9Im5vbmUiIHN0cm9rZT0icmdiYSgyMTIsMTY4LDgxLDAuMTUpIiBzdHJva2Utd2lkdGg9IjEiLz4KICA8Y2lyY2xlIGN4PSIxNzAiIGN5PSIxNjciIHI9IjE0NSIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJyZ2JhKDIxMiwxNjgsODEsMC4wOCkiIHN0cm9rZS13aWR0aD0iMSIvPgoKICA8IS0tIOmHkeiJsuOBrui8neOBjeODkeODvOODhuOCo+OCr+ODqyAtLT4KICA8ZyBvcGFjaXR5PSIwLjYiPgogICAgPGNpcmNsZSBjeD0iNTAiIGN5PSI2MCIgcj0iMS41IiBmaWxsPSIjZjVkOThhIi8+CiAgICA8Y2lyY2xlIGN4PSIyOTAiIGN5PSI4MCIgcj0iMSIgZmlsbD0iI2Y1ZDk4YSIvPgogICAgPGNpcmNsZSBjeD0iNDAiIGN5PSIyMDAiIHI9IjEuMiIgZmlsbD0iI2Q0YTg1MSIvPgogICAgPGNpcmNsZSBjeD0iMzAwIiBjeT0iMjUwIiByPSIxLjUiIGZpbGw9IiNmNWQ5OGEiLz4KICAgIDxjaXJjbGUgY3g9IjI4MCIgY3k9IjQwIiByPSIxIiBmaWxsPSIjZDRhODUxIi8+CiAgICA8Y2lyY2xlIGN4PSI2MCIgY3k9IjI4MCIgcj0iMS4zIiBmaWxsPSIjZjVkOThhIi8+CiAgICA8Y2lyY2xlIGN4PSIyMCIgY3k9IjE1MCIgcj0iMC44IiBmaWxsPSIjZDRhODUxIi8+CiAgICA8Y2lyY2xlIGN4PSIzMjAiIGN5PSIxODAiIHI9IjAuOCIgZmlsbD0iI2Q0YTg1MSIvPgogIDwvZz4KCiAgPCEtLSDmoZzjga7oirHjgbPjgonoo4Xpo74gLS0+CiAgPGcgb3BhY2l0eT0iMC4yNSIgZmlsbD0iI2Q0YTg1MSI+CiAgICA8cGF0aCBkPSJNIDIzMCA4MCBRIDIzNSA3NSAyNDAgODAgUSAyMzUgODUgMjMwIDgwIFoiLz4KICAgIDxwYXRoIGQ9Ik0gMTAwIDkwIFEgMTA1IDg1IDExMCA5MCBRIDEwNSA5NSAxMDAgOTAgWiIvPgogICAgPHBhdGggZD0iTSAyNTAgMjUwIFEgMjU1IDI0NSAyNjAgMjUwIFEgMjU1IDI1NSAyNTAgMjUwIFoiLz4KICA8L2c+CgogIDwhLS0g5aSW5YG044Gu6YeR44Oh44OA44Or5p6gIC0tPgogIDxjaXJjbGUgY3g9IjE3MCIgY3k9IjE2NyIgcj0iMTI1IiBmaWxsPSJub25lIiBzdHJva2U9InVybCgjZ29sZEZyYW1lKSIgc3Ryb2tlLXdpZHRoPSI2Ii8+CiAgPGNpcmNsZSBjeD0iMTcwIiBjeT0iMTY3IiByPSIxMjAiIGZpbGw9Im5vbmUiIHN0cm9rZT0iIzhiNjkxNCIgc3Ryb2tlLXdpZHRoPSIxIiBvcGFjaXR5PSIwLjYiLz4KICA8Y2lyY2xlIGN4PSIxNzAiIGN5PSIxNjciIHI9IjEzMCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjOGI2OTE0IiBzdHJva2Utd2lkdGg9IjEiIG9wYWNpdHk9IjAuNCIvPgoKICA8IS0tIOODoeODgOODq+WGhemDqCAtLT4KICA8Y2lyY2xlIGN4PSIxNzAiIGN5PSIxNjciIHI9IjExOSIgZmlsbD0idXJsKCNtZWRhbEdsb3cpIi8+CgogIDwhLS0g44Oh44OA44Or5YaF6YOo44Gu5ZKM5p+E44OR44K/44O844Oz77yI6Z2S5rW35rOi6aKo77yJIC0tPgogIDxnIG9wYWNpdHk9IjAuMTIiIHN0cm9rZT0iI2Q0YTg1MSIgc3Ryb2tlLXdpZHRoPSIxIiBmaWxsPSJub25lIj4KICAgIDxwYXRoIGQ9Ik0gOTAgMTY3IFEgMTEwIDE0NyAxMzAgMTY3Ii8+CiAgICA8cGF0aCBkPSJNIDEzMCAxNjcgUSAxNTAgMTQ3IDE3MCAxNjciLz4KICAgIDxwYXRoIGQ9Ik0gMTcwIDE2NyBRIDE5MCAxNDcgMjEwIDE2NyIvPgogICAgPHBhdGggZD0iTSAyMTAgMTY3IFEgMjMwIDE0NyAyNTAgMTY3Ii8+CiAgICA8cGF0aCBkPSJNIDEwMCAxODcgUSAxMjAgMTY3IDE0MCAxODciLz4KICAgIDxwYXRoIGQ9Ik0gMTQwIDE4NyBRIDE2MCAxNjcgMTgwIDE4NyIvPgogICAgPHBhdGggZD0iTSAxODAgMTg3IFEgMjAwIDE2NyAyMjAgMTg3Ii8+CiAgPC9nPgoKICA8IS0tID09PT09IOODk+ODvOODq+OCuOODp+ODg+OCrSA9PT09PSAtLT4KICA8IS0tIOOCuOODp+ODg+OCreOBruWPluOBo+aJi++8iOW+jOOCjeWBtO+8iSAtLT4KICA8cGF0aCBkPSJNIDIyMCAxMzAgUSAyNTAgMTMwIDI1MiAxNjUgUSAyNTIgMjAwIDIyMiAyMDAiCiAgICAgICAgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYTg5ODc4IiBzdHJva2Utd2lkdGg9IjYiIG9wYWNpdHk9IjAuNyIvPgogIDxwYXRoIGQ9Ik0gMjIwIDEzNSBRIDI0NSAxMzUgMjQ3IDE2NSBRIDI0NyAxOTUgMjIyIDE5NSIKICAgICAgICBmaWxsPSJub25lIiBzdHJva2U9InJnYmEoMjU1LDI1NSwyNTUsMC4zKSIgc3Ryb2tlLXdpZHRoPSIyIi8+CgogIDwhLS0g44K444On44OD44Kt5pys5L2T77yI44Ks44Op44K577yJIC0tPgogIDwhLS0g5aSW5YG044Gu6Lyq6YOtIC0tPgogIDxwYXRoIGQ9Ik0gMTA1IDExNQogICAgICAgICAgIEwgMjI1IDExNQogICAgICAgICAgIEwgMjMwIDIzMAogICAgICAgICAgIFEgMjMwIDI0MCAyMjAgMjQwCiAgICAgICAgICAgTCAxMTAgMjQwCiAgICAgICAgICAgUSAxMDAgMjQwIDEwMCAyMzAgWiIKICAgICAgICBmaWxsPSJyZ2JhKDAsMCwwLDAuMikiIHN0cm9rZT0iIzhiNjkxNCIgc3Ryb2tlLXdpZHRoPSIxLjUiLz4KCiAgPCEtLSDjg5Pjg7zjg6vjga7mtrLkvZMgLS0+CiAgPHBhdGggZD0iTSAxMDggMTM1CiAgICAgICAgICAgTCAyMjIgMTM1CiAgICAgICAgICAgTCAyMjYgMjI4CiAgICAgICAgICAgUSAyMjYgMjM2IDIxOCAyMzYKICAgICAgICAgICBMIDExMiAyMzYKICAgICAgICAgICBRIDEwNCAyMzYgMTA0IDIyOCBaIgogICAgICAgIGZpbGw9InVybCgjYmVlckxpcXVpZCkiLz4KCiAgPCEtLSDmtrLkvZPjga7kuK3jga7msJfms6EgLS0+CiAgPGcgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjUpIj4KICAgIDxjaXJjbGUgY3g9IjEzNSIgY3k9IjE4MCIgcj0iMi41Ii8+CiAgICA8Y2lyY2xlIGN4PSIxOTUiIGN5PSIyMDAiIHI9IjIiLz4KICAgIDxjaXJjbGUgY3g9IjE1NSIgY3k9IjIyMCIgcj0iMS44Ii8+CiAgICA8Y2lyY2xlIGN4PSIxODAiIGN5PSIxNzAiIHI9IjEuNSIvPgogICAgPGNpcmNsZSBjeD0iMTI1IiBjeT0iMjEwIiByPSIxLjUiLz4KICAgIDxjaXJjbGUgY3g9IjIwNSIgY3k9IjE3NSIgcj0iMiIvPgogICAgPGNpcmNsZSBjeD0iMTY1IiBjeT0iMTk1IiByPSIxLjIiLz4KICAgIDxjaXJjbGUgY3g9IjE0NSIgY3k9IjE1NSIgcj0iMS41Ii8+CiAgICA8Y2lyY2xlIGN4PSIxOTAiIGN5PSIyMjUiIHI9IjEuOCIvPgogIDwvZz4KCiAgPCEtLSDjgrjjg6fjg4Pjgq3jga7jgqzjg6njgrnjga7jg4/jgqTjg6njgqTjg4jvvIjlt6blgbTvvIkgLS0+CiAgPHBhdGggZD0iTSAxMTIgMTI1CiAgICAgICAgICAgTCAxMTggMTI1CiAgICAgICAgICAgTCAxMjIgMjM1CiAgICAgICAgICAgTCAxMTYgMjM1IFoiCiAgICAgICAgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjM1KSIvPgoKICA8IS0tIOOCuOODp+ODg+OCreOBruOCrOODqeOCueOBrumdou+8iOe4puOBrue3muOBp+eri+S9k+aEn++8iSAtLT4KICA8bGluZSB4MT0iMTM1IiB5MT0iMTQwIiB4Mj0iMTM4IiB5Mj0iMjM1IiBzdHJva2U9InJnYmEoMjU1LDI1NSwyNTUsMC4xNSkiIHN0cm9rZS13aWR0aD0iMSIvPgogIDxsaW5lIHgxPSIxNzAiIHkxPSIxNDAiIHgyPSIxNzIiIHkyPSIyMzUiIHN0cm9rZT0icmdiYSgyNTUsMjU1LDI1NSwwLjEpIiBzdHJva2Utd2lkdGg9IjEiLz4KICA8bGluZSB4MT0iMjA1IiB5MT0iMTQwIiB4Mj0iMjA4IiB5Mj0iMjM1IiBzdHJva2U9InJnYmEoMjU1LDI1NSwyNTUsMC4xNSkiIHN0cm9rZS13aWR0aD0iMSIvPgoKICA8IS0tIOazoe+8iOS4iumDqO+8iSAtLT4KICA8ZWxsaXBzZSBjeD0iMTY1IiBjeT0iMTI1IiByeD0iNjUiIHJ5PSIxOCIgZmlsbD0idXJsKCNmb2FtR3JhZCkiLz4KICA8IS0tIOazoeOBruWHueWHuCAtLT4KICA8Y2lyY2xlIGN4PSIxMjAiIGN5PSIxMTUiIHI9IjEwIiBmaWxsPSIjZmZmZmZmIiBvcGFjaXR5PSIwLjk1Ii8+CiAgPGNpcmNsZSBjeD0iMTM4IiBjeT0iMTA4IiByPSI5IiBmaWxsPSIjZjVlYWQwIiBvcGFjaXR5PSIwLjk1Ii8+CiAgPGNpcmNsZSBjeD0iMTU1IiBjeT0iMTEyIiByPSIxMSIgZmlsbD0iI2ZmZmZmZiIgb3BhY2l0eT0iMC45NSIvPgogIDxjaXJjbGUgY3g9IjE3MiIgY3k9IjEwNiIgcj0iMTAiIGZpbGw9IiNmNWVhZDAiIG9wYWNpdHk9IjAuOTUiLz4KICA8Y2lyY2xlIGN4PSIxOTAiIGN5PSIxMTAiIHI9IjkiIGZpbGw9IiNmZmZmZmYiIG9wYWNpdHk9IjAuOTUiLz4KICA8Y2lyY2xlIGN4PSIyMDUiIGN5PSIxMTUiIHI9IjEwIiBmaWxsPSIjZjVlYWQwIiBvcGFjaXR5PSIwLjk1Ii8+CiAgPGNpcmNsZSBjeD0iMTMwIiBjeT0iMTIwIiByPSI2IiBmaWxsPSIjZmZmZmZmIiBvcGFjaXR5PSIwLjgiLz4KICA8Y2lyY2xlIGN4PSIxODAiIGN5PSIxMTgiIHI9IjciIGZpbGw9IiNmZmZmZmYiIG9wYWNpdHk9IjAuOCIvPgogIDxjaXJjbGUgY3g9IjIwMCIgY3k9IjEyMiIgcj0iNSIgZmlsbD0iI2Y1ZWFkMCIgb3BhY2l0eT0iMC44Ii8+CgogIDwhLS0g5rOh44Gu5bCP44GV44Gq44OP44Kk44Op44Kk44OIIC0tPgogIDxjaXJjbGUgY3g9IjEzOCIgY3k9IjEwNCIgcj0iMyIgZmlsbD0iI2ZmZmZmZiIvPgogIDxjaXJjbGUgY3g9IjE3MiIgY3k9IjEwMiIgcj0iMyIgZmlsbD0iI2ZmZmZmZiIvPgogIDxjaXJjbGUgY3g9IjE1NSIgY3k9IjEwOCIgcj0iMi41IiBmaWxsPSIjZmZmZmZmIi8+CgogIDwhLS0g44K444On44OD44Kt44Gu5bqV44Gu44GK55q/77yI44Kz44O844K544K/44O86aKo77yJIC0tPgogIDxlbGxpcHNlIGN4PSIxNjUiIGN5PSIyNDgiIHJ4PSI3OCIgcnk9IjEwIiBmaWxsPSIjM2EyNDE4IiBzdHJva2U9IiM4YjY5MTQiIHN0cm9rZS13aWR0aD0iMS41Ii8+CiAgPGVsbGlwc2UgY3g9IjE2NSIgY3k9IjI0NiIgcng9Ijc0IiByeT0iNyIgZmlsbD0iIzVhM2ExYSIvPgogIDxlbGxpcHNlIGN4PSIxNjUiIGN5PSIyNDUiIHJ4PSI2OCIgcnk9IjQiIGZpbGw9InJnYmEoMjEyLDE2OCw4MSwwLjIpIi8+CgogIDwhLS0g5YWo5L2T44Gr6JaE44GE5YWJ5rKi44Kq44O844OQ44O844Os44KkIC0tPgogIDxyYWRpYWxHcmFkaWVudCBpZD0idG9wR2xvdyIgY3g9IjUwJSIgY3k9IjIwJSIgcj0iNTAlIj4KICAgIDxzdG9wIG9mZnNldD0iMCUiIHN0b3AtY29sb3I9InJnYmEoMjQ1LDIxNywxMzgsMC4xNSkiLz4KICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0icmdiYSgwLDAsMCwwKSIvPgogIDwvcmFkaWFsR3JhZGllbnQ+CiAgPGNpcmNsZSBjeD0iMTcwIiBjeT0iMTY3IiByPSIxMTkiIGZpbGw9InVybCgjdG9wR2xvdykiLz4KPC9zdmc+Cg==',
      color: '#5a3a1a'
    }
  };

  // ===== 状態管理 =====
  let isSpinning = false;
  let reelHeights = [0, 0, 0]; // 各リールの1コマの高さ

  const startBtn = document.getElementById('startBtn');
  const statusText = document.getElementById('statusText');
  const winFlash = document.getElementById('winFlash');
  const couponOverlay = document.getElementById('couponOverlay');
  const couponUseBtn = document.getElementById('couponUseBtn');
  const confettiContainer = document.getElementById('confettiContainer');

  // ===================================================================
  // 当選本数カウント機能（端末内localStorageに日付別で記録）
  // ===================================================================
  const STORAGE_KEY = 'sushi_roulette_counts_v1';

  function todayStr() {
    const d = new Date();
    const y = d.getFullYear();
    const m = String(d.getMonth() + 1).padStart(2, '0');
    const day = String(d.getDate()).padStart(2, '0');
    return `${y}-${m}-${day}`;
  }

  // 全データ読み込み: { "2026-05-28": {tuna,salmon,tamago,drink}, ... }
  function loadCounts() {
    try {
      const raw = localStorage.getItem(STORAGE_KEY);
      return raw ? JSON.parse(raw) : {};
    } catch (e) {
      return {};
    }
  }

  function saveCounts(data) {
    try {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(data));
    } catch (e) {
      // ストレージ不可環境（プライベートモード等）でも抽選自体は継続
      console.warn('カウント保存に失敗しました', e);
    }
  }

  // 当選を1件記録
  function recordWin(prizeKey) {
    const data = loadCounts();
    const t = todayStr();
    if (!data[t]) data[t] = { tuna: 0, salmon: 0, tamago: 0, drink: 0 };
    if (data[t][prizeKey] === undefined) data[t][prizeKey] = 0;
    data[t][prizeKey]++;
    saveCounts(data);
  }

  // 集計取得（scope: 'today' | 'total'）
  function getTally(scope) {
    const data = loadCounts();
    const sum = { tuna: 0, salmon: 0, tamago: 0, drink: 0 };
    if (scope === 'today') {
      const t = data[todayStr()];
      if (t) for (const k in sum) sum[k] += (t[k] || 0);
    } else {
      for (const date in data) {
        for (const k in sum) sum[k] += (data[date][k] || 0);
      }
    }
    return sum;
  }

  // ===================================================================
  // 当選確率の保存・読み込み（localStorageで永続化）
  // ===================================================================
  const PROB_KEY = 'sushi_roulette_probs_v1';
  const DEFAULT_PROBS = { tuna: 1, salmon: 3, tamago: 5 };

  function loadProbs() {
    try {
      const raw = localStorage.getItem(PROB_KEY);
      if (raw) {
        const p = JSON.parse(raw);
        const sum = (p.tuna || 0) + (p.salmon || 0) + (p.tamago || 0);
        if (sum > 0 && sum <= 100) return p;
      }
    } catch (e) {}
    return { ...DEFAULT_PROBS };
  }

  function saveProbs(p) {
    try { localStorage.setItem(PROB_KEY, JSON.stringify(p)); } catch (e) {}
  }

  // ===================================================================
  // 当選商品の設定（localStorageで永続化）
  // PRIZESオブジェクトの prizeName / discount / desc を上書きする
  // ===================================================================
  const PRIZE_KEY = 'sushi_roulette_prizes_v1';
  // デフォルト商品内容（リセット用に保持）
  const DEFAULT_PRIZE_INFO = {
    tuna:   { prizeName: PRIZES.tuna.prizeName,   discount: PRIZES.tuna.discount,   desc: PRIZES.tuna.desc },
    salmon: { prizeName: PRIZES.salmon.prizeName, discount: PRIZES.salmon.discount, desc: PRIZES.salmon.desc },
    tamago: { prizeName: PRIZES.tamago.prizeName, discount: PRIZES.tamago.discount, desc: PRIZES.tamago.desc },
    drink:  { prizeName: PRIZES.drink.prizeName,  discount: PRIZES.drink.discount,  desc: PRIZES.drink.desc },
  };

  function loadPrizeInfo() {
    try {
      const raw = localStorage.getItem(PRIZE_KEY);
      if (raw) {
        const saved = JSON.parse(raw);
        // デフォルトをベースに保存値をマージ（欠損キー対策）
        const merged = {};
        for (const k of ['tuna','salmon','tamago','drink']) {
          merged[k] = { ...DEFAULT_PRIZE_INFO[k], ...(saved[k] || {}) };
        }
        return merged;
      }
    } catch (e) {}
    // ディープコピーで返す
    return JSON.parse(JSON.stringify(DEFAULT_PRIZE_INFO));
  }

  function savePrizeInfo(info) {
    try { localStorage.setItem(PRIZE_KEY, JSON.stringify(info)); } catch (e) {}
  }

  // ===================================================================
  // パスワード管理
  // ===================================================================
  const PW_KEY = 'sushi_roulette_pw_v1';
  const DEFAULT_PW = '1234';

  function loadPw() {
    try {
      const v = localStorage.getItem(PW_KEY);
      if (v && /^\d{4}$/.test(v)) return v;
    } catch (e) {}
    return DEFAULT_PW;
  }
  function savePw(pw) {
    try { localStorage.setItem(PW_KEY, pw); } catch (e) {}
  }

  // ===== パスワード入力モーダルの制御 =====
  const pwOverlay = document.getElementById('pwOverlay');
  let pwInput = '';

  function openPwModal() {
    pwInput = '';
    updatePwDots();
    document.getElementById('pwError').textContent = '';
    pwOverlay.classList.add('show');
  }
  function closePwModal() {
    pwInput = '';
    updatePwDots();
    pwOverlay.classList.remove('show');
  }

  function updatePwDots() {
    for (let i = 0; i < 4; i++) {
      const dot = document.getElementById('dot' + i);
      dot.classList.toggle('filled', i < pwInput.length);
    }
  }

  // テンキーの数字ボタン
  document.querySelectorAll('.pw-key[data-n]').forEach(btn => {
    btn.addEventListener('click', () => {
      if (pwInput.length >= 4) return;
      pwInput += btn.dataset.n;
      updatePwDots();
      // 4桁揃ったら自動チェック
      if (pwInput.length === 4) {
        setTimeout(() => {
          if (pwInput === loadPw()) {
            closePwModal();
            openAdmin();
          } else {
            document.getElementById('pwError').textContent = 'パスワードが違います';
            // エラー時は少し待ってリセット
            setTimeout(() => {
              pwInput = '';
              updatePwDots();
              document.getElementById('pwError').textContent = '';
            }, 800);
          }
        }, 80); // ドットが4つ点灯した状態を一瞬見せる
      }
    });
  });

  // 削除ボタン
  document.getElementById('pwDel').addEventListener('click', () => {
    if (pwInput.length > 0) {
      pwInput = pwInput.slice(0, -1);
      updatePwDots();
      document.getElementById('pwError').textContent = '';
    }
  });

  // キャンセルボタン
  document.getElementById('pwCancel').addEventListener('click', closePwModal);
  function applyPrizeInfo() {
    const info = loadPrizeInfo();
    for (const k of ['tuna','salmon','tamago','drink']) {
      PRIZES[k].prizeName = info[k].prizeName;
      PRIZES[k].discount  = info[k].discount;
      PRIZES[k].desc      = info[k].desc;
    }
    updatePrizeList();
  }

  // 賞品一覧（初期画面）の表示を最新の商品設定に更新
  function updatePrizeList() {
    const setText = (id, txt) => {
      const el = document.getElementById(id);
      if (el) el.textContent = txt;
    };
    setText('listNameTuna',   PRIZES.tuna.prizeName);
    setText('listDescTuna',   `${PRIZES.tuna.discount}%引きクーポン`);
    setText('listNameSalmon', PRIZES.salmon.prizeName);
    setText('listDescSalmon', `${PRIZES.salmon.discount}%引きクーポン`);
    setText('listNameTamago', PRIZES.tamago.prizeName);
    setText('listDescTamago', `${PRIZES.tamago.discount}%引きクーポン`);
    setText('listNameDrink',  PRIZES.drink.prizeName);
  }

  // ===================================================================
  // 効果音エンジン（Web Audio API / 外部ファイル不要）
  // ===================================================================
  const SFX = (() => {
    let ctx = null;

    function getCtx() {
      if (!ctx) ctx = new (window.AudioContext || window.webkitAudioContext)();
      // iOSなどで停止している場合は再開
      if (ctx.state === 'suspended') ctx.resume();
      return ctx;
    }

    // 基本ユーティリティ: ゲイン付きで音を鳴らす
    function gain(ctx, val, t) {
      const g = ctx.createGain();
      g.gain.setValueAtTime(val, t);
      return g;
    }

    // ── スタート音: レバーを引くような「カチッ＋ウィーン」 ──
    function start() {
      const c = getCtx();
      const now = c.currentTime;

      // クリック感（短いノイズ）
      const bufLen = c.sampleRate * 0.06;
      const buf = c.createBuffer(1, bufLen, c.sampleRate);
      const data = buf.getChannelData(0);
      for (let i = 0; i < bufLen; i++) {
        data[i] = (Math.random() * 2 - 1) * Math.exp(-i / (bufLen * 0.25));
      }
      const src = c.createBufferSource();
      src.buffer = buf;
      const g = c.createGain();
      g.gain.setValueAtTime(0.35, now);
      src.connect(g); g.connect(c.destination);
      src.start(now);

      // 上昇するホイール音（起動感）
      const osc = c.createOscillator();
      osc.type = 'sawtooth';
      osc.frequency.setValueAtTime(80, now);
      osc.frequency.exponentialRampToValueAtTime(320, now + 0.35);
      const g2 = c.createGain();
      g2.gain.setValueAtTime(0.0, now);
      g2.gain.linearRampToValueAtTime(0.18, now + 0.04);
      g2.gain.exponentialRampToValueAtTime(0.001, now + 0.38);
      osc.connect(g2); g2.connect(c.destination);
      osc.start(now); osc.stop(now + 0.4);
    }

    // ── リール回転音: スロット的なカラカラ音（ループ） ──
    // startReel / stopReel で制御
    const reelSources = [];
    function startReelSound() {
      const c = getCtx();
      // リズミカルなティック音を setInterval で連打
      // (1リールにつき1つのintervalIDを返す)
      let fast = true;
      const id = setInterval(() => {
        const now = c.currentTime;
        const osc = c.createOscillator();
        osc.type = 'square';
        osc.frequency.setValueAtTime(fast ? 1200 : 900, now);
        const g = c.createGain();
        g.gain.setValueAtTime(0.07, now);
        g.gain.exponentialRampToValueAtTime(0.001, now + 0.025);
        osc.connect(g); g.connect(c.destination);
        osc.start(now); osc.stop(now + 0.03);
        fast = !fast;
      }, 60);
      return id;
    }
    function stopReelInterval(id) {
      clearInterval(id);
    }

    // ── リール停止音: 「コトン」という木の塊が落ちる感じ ──
    function reelStop(reelIndex) {
      const c = getCtx();
      const now = c.currentTime;

      // 低め・短いアタック音
      const freq = [220, 196, 175][reelIndex] || 196;
      const osc = c.createOscillator();
      osc.type = 'triangle';
      osc.frequency.setValueAtTime(freq * 2.5, now);
      osc.frequency.exponentialRampToValueAtTime(freq, now + 0.08);
      const g = c.createGain();
      g.gain.setValueAtTime(0.5, now);
      g.gain.exponentialRampToValueAtTime(0.001, now + 0.22);
      osc.connect(g); g.connect(c.destination);
      osc.start(now); osc.stop(now + 0.25);

      // クリック感の補強
      const bufLen = Math.floor(c.sampleRate * 0.04);
      const buf = c.createBuffer(1, bufLen, c.sampleRate);
      const d = buf.getChannelData(0);
      for (let i = 0; i < bufLen; i++) d[i] = (Math.random()*2-1) * Math.exp(-i/(bufLen*0.15));
      const ns = c.createBufferSource();
      ns.buffer = buf;
      const ng = c.createGain();
      ng.gain.setValueAtTime(0.2, now);
      ns.connect(ng); ng.connect(c.destination);
      ns.start(now);
    }

    // ── 当選ファンファーレ: 明るい上昇アルペジオ ──
    function fanfare() {
      const c = getCtx();
      const now = c.currentTime;

      // ジングルのメロディ音符（C5 E5 G5 C6）
      const notes = [523.25, 659.25, 783.99, 1046.50];
      const durations = [0.12, 0.12, 0.12, 0.38];
      let t = now;

      notes.forEach((freq, i) => {
        // メイン音
        const osc = c.createOscillator();
        osc.type = 'triangle';
        osc.frequency.setValueAtTime(freq, t);
        const g = c.createGain();
        g.gain.setValueAtTime(0.0, t);
        g.gain.linearRampToValueAtTime(0.45, t + 0.02);
        g.gain.exponentialRampToValueAtTime(0.001, t + durations[i] + 0.05);
        osc.connect(g); g.connect(c.destination);
        osc.start(t); osc.stop(t + durations[i] + 0.1);

        // 倍音（1オクターブ上）
        const osc2 = c.createOscillator();
        osc2.type = 'sine';
        osc2.frequency.setValueAtTime(freq * 2, t);
        const g2 = c.createGain();
        g2.gain.setValueAtTime(0.0, t);
        g2.gain.linearRampToValueAtTime(0.15, t + 0.02);
        g2.gain.exponentialRampToValueAtTime(0.001, t + durations[i] + 0.05);
        osc2.connect(g2); g2.connect(c.destination);
        osc2.start(t); osc2.stop(t + durations[i] + 0.1);

        t += durations[i] * 0.9;
      });

      // 最後の音の後に輝き感（高周波シマー）
      const shimmerStart = now + 0.36;
      for (let i = 0; i < 6; i++) {
        const so = c.createOscillator();
        so.type = 'sine';
        so.frequency.setValueAtTime(2000 + Math.random() * 1500, shimmerStart + i * 0.04);
        const sg = c.createGain();
        sg.gain.setValueAtTime(0.06, shimmerStart + i * 0.04);
        sg.gain.exponentialRampToValueAtTime(0.001, shimmerStart + i * 0.04 + 0.18);
        so.connect(sg); sg.connect(c.destination);
        so.start(shimmerStart + i * 0.04);
        so.stop(shimmerStart + i * 0.04 + 0.2);
      }
    }

    // ── 参加賞（外れ）: 優しい「ポロン」 ──
    function consolation() {
      const c = getCtx();
      const now = c.currentTime;

      // C5 → A4 の短い2音（少し残念だけど優しい）
      [[523.25, 0], [440, 0.15]].forEach(([freq, delay]) => {
        const osc = c.createOscillator();
        osc.type = 'sine';
        osc.frequency.setValueAtTime(freq, now + delay);
        const g = c.createGain();
        g.gain.setValueAtTime(0.0, now + delay);
        g.gain.linearRampToValueAtTime(0.3, now + delay + 0.02);
        g.gain.exponentialRampToValueAtTime(0.001, now + delay + 0.45);
        osc.connect(g); g.connect(c.destination);
        osc.start(now + delay); osc.stop(now + delay + 0.5);
      });
    }

    // ── クーポン表示音: キラキラっとしたbell音 ──
    function couponReveal() {
      const c = getCtx();
      const now = c.currentTime;

      const freqs = [1318.5, 1567.98, 2093.0, 2637.02];
      freqs.forEach((freq, i) => {
        const osc = c.createOscillator();
        osc.type = 'sine';
        osc.frequency.setValueAtTime(freq, now + i * 0.06);
        const g = c.createGain();
        g.gain.setValueAtTime(0.0, now + i * 0.06);
        g.gain.linearRampToValueAtTime(0.2, now + i * 0.06 + 0.01);
        g.gain.exponentialRampToValueAtTime(0.001, now + i * 0.06 + 0.5);
        osc.connect(g); g.connect(c.destination);
        osc.start(now + i * 0.06); osc.stop(now + i * 0.06 + 0.55);
      });
    }

    // ── 利用済みボタン: 軽い「ポップ」 ──
    function used() {
      const c = getCtx();
      const now = c.currentTime;
      const osc = c.createOscillator();
      osc.type = 'sine';
      osc.frequency.setValueAtTime(400, now);
      osc.frequency.exponentialRampToValueAtTime(200, now + 0.1);
      const g = c.createGain();
      g.gain.setValueAtTime(0.25, now);
      g.gain.exponentialRampToValueAtTime(0.001, now + 0.12);
      osc.connect(g); g.connect(c.destination);
      osc.start(now); osc.stop(now + 0.15);
    }

    return { start, startReelSound, stopReelInterval, reelStop, fanfare, consolation, couponReveal, used };
  })();

  // 各リールに大量の画像を積み上げて、CSS transformで縦スクロールさせる
  // 末尾の表示位置に「結果のシンボル」を配置する
  function buildStrip(reelIndex, finalSymbol) {
    const strip = document.getElementById('strip' + reelIndex);
    strip.style.transition = 'none';
    strip.style.transform = 'translateY(0)';
    strip.innerHTML = '';

    // 1コマあたりのサイズ取得
    const reelWindow = document.getElementById('reel' + reelIndex);
    const cellSize = reelWindow.clientWidth;
    reelHeights[reelIndex] = cellSize;

    // 多めにシンボルを並べる（回転中の見た目用）
    // 最後のコマが「最終的に窓に表示されるシンボル」になる
    const TOTAL_CELLS = 40;
    const cells = [];
    for (let i = 0; i < TOTAL_CELLS - 1; i++) {
      // ランダムなシンボル
      cells.push(SYMBOLS[Math.floor(Math.random() * 3)]);
    }
    cells.push(finalSymbol); // 最後のコマが最終結果

    cells.forEach(sym => {
      const img = document.createElement('img');
      img.src = IMG[sym];
      img.alt = sym;
      strip.appendChild(img);
    });

    return { cellSize, totalCells: TOTAL_CELLS };
  }

  // ===== 抽選結果の決定（確率はlocalStorageから動的に読み込む） =====
  function determineOutcome() {
    const p = loadProbs();
    const r = Math.random() * 100;
    const c1 = p.tuna;
    const c2 = c1 + p.salmon;
    const c3 = c2 + p.tamago;
    if (r < c1)      return { type: 'win', symbol: 'tuna' };
    else if (r < c2) return { type: 'win', symbol: 'salmon' };
    else if (r < c3) return { type: 'win', symbol: 'tamago' };
    else             return { type: 'lose' };
  }

  // 外れの場合の3つのシンボルを決定（揃わないようにする）
  // ただし最後のリールだけ違うシンボルにして「期待感」を演出
  function buildLoseSymbols() {
    // 50%の確率で「2つ揃ってもう一つ違う」パターン（ハラハラ演出）
    // 50%の確率で「全部バラバラ」
    if (Math.random() < 0.5) {
      // ハラハラパターン: 最初の2つが同じ、最後が違う
      const sameSym = SYMBOLS[Math.floor(Math.random() * 3)];
      const others = SYMBOLS.filter(s => s !== sameSym);
      const lastSym = others[Math.floor(Math.random() * 2)];
      return [sameSym, sameSym, lastSym];
    } else {
      // 完全バラバラ
      const shuffled = [...SYMBOLS].sort(() => Math.random() - 0.5);
      return shuffled;
    }
  }

  // ===== ルーレット開始 =====
  function startRoulette() {
    if (isSpinning) return;
    isSpinning = true;
    startBtn.disabled = true;
    statusText.textContent = '抽選中...';

    // スタート効果音
    SFX.start();

    // リール窓のwin状態をリセット
    for (let i = 0; i < 3; i++) {
      document.getElementById('reel' + i).classList.remove('win');
    }

    // 結果決定
    const outcome = determineOutcome();
    let finalSymbols;
    if (outcome.type === 'win') {
      finalSymbols = [outcome.symbol, outcome.symbol, outcome.symbol];
    } else {
      finalSymbols = buildLoseSymbols();
    }

    // 各リールのストリップ構築
    const reelInfos = [];
    for (let i = 0; i < 3; i++) {
      reelInfos.push(buildStrip(i, finalSymbols[i]));
    }

    // 停止タイミング（左→中→右）
    const stopTimings = [1400, 2300, 3300]; // ms

    // リール回転音スタート（全リール共通で1つのループ音）
    const reelIntervalId = SFX.startReelSound();

    // 強制リフロー後に全リール一斉スタート
    requestAnimationFrame(() => {
      requestAnimationFrame(() => {
        for (let i = 0; i < 3; i++) {
          spinReel(i, reelInfos[i], stopTimings[i]);
        }
      });
    });

    // 各リール停止タイミングで音を鳴らす
    stopTimings.forEach((timing, i) => {
      setTimeout(() => {
        SFX.reelStop(i);
        // 最後のリールが止まったらループ音も止める
        if (i === 2) SFX.stopReelInterval(reelIntervalId);
      }, timing);
    });

    // 全リール停止後の処理
    setTimeout(() => {
      onAllReelsStopped(outcome, finalSymbols);
    }, stopTimings[2] + 200);
  }

  // ===== 個別リールの回転と停止 =====
  function spinReel(reelIndex, info, stopAfterMs) {
    const strip = document.getElementById('strip' + reelIndex);
    const { cellSize, totalCells } = info;
    // 最終位置: 最後のコマが窓内に来る位置
    const finalY = -(totalCells - 1) * cellSize;

    // CSS transitionで一気に最終位置まで移動（ease-outで自然な減速）
    strip.style.transition = `transform ${stopAfterMs}ms cubic-bezier(0.15, 0.6, 0.25, 1)`;
    strip.style.transform = `translateY(${finalY}px)`;

    // 停止音/着地演出
    setTimeout(() => {
      // 軽い揺れアニメーション
      strip.style.transition = 'transform 0.12s ease-out';
      strip.style.transform = `translateY(${finalY - 6}px)`;
      setTimeout(() => {
        strip.style.transform = `translateY(${finalY}px)`;
        // 停止時のステータス更新
        if (reelIndex < 2) {
          statusText.textContent = `${reelIndex + 1}つ目 停止...`;
        } else {
          statusText.textContent = '結果発表...';
        }
      }, 120);
    }, stopAfterMs);
  }

  // ===== 全リール停止後 =====
  function onAllReelsStopped(outcome, finalSymbols) {
    const isWin = outcome.type === 'win';

    if (isWin) {
      statusText.textContent = '★ 当 選 ★';
      for (let i = 0; i < 3; i++) {
        document.getElementById('reel' + i).classList.add('win');
      }
      winFlash.classList.add('active');
      setTimeout(() => winFlash.classList.remove('active'), 800);
      launchConfetti();
      SFX.fanfare(); // 当選ファンファーレ
    } else {
      statusText.textContent = '残念...参加賞をどうぞ';
      SFX.consolation(); // 参加賞の優しい音
    }

    // 3秒後にクーポン表示
    setTimeout(() => {
      const prizeKey = isWin ? outcome.symbol : 'drink';
      recordWin(prizeKey);
      SFX.couponReveal(); // クーポン表示音
      showCoupon(prizeKey);
    }, 3000);
  }

  // ===== クーポン表示 =====
  function showCoupon(prizeKey) {
    const prize = PRIZES[prizeKey];

    document.getElementById('couponGrade').textContent = prize.grade;
    document.getElementById('couponTitle').textContent = prize.title;
    document.getElementById('couponPrizeName').textContent = prize.prizeName;
    document.getElementById('couponDesc').textContent = prize.desc;

    const discountEl = document.getElementById('couponDiscount');
    if (prize.discount) {
      discountEl.innerHTML = `${prize.discount}<span class="pct">%</span> <span class="label">OFF</span>`;
    } else {
      discountEl.innerHTML = `<span class="label" style="font-size:24px;">FREE</span><br><span class="label" style="font-size:13px;">DRINK</span>`;
    }

    const imgWrap = document.getElementById('couponImg');
    const imgSrc = document.getElementById('couponImgSrc');
    if (prize.img) {
      imgSrc.src = prize.img;
      imgWrap.style.display = 'block';
    } else {
      imgWrap.style.display = 'none';
    }

    couponOverlay.classList.add('show');
  }

  // ===== クーポン利用済み =====
  function onCouponUsed() {
    SFX.used(); // 軽いポップ音
    couponOverlay.classList.remove('show');
    setTimeout(() => {
      isSpinning = false;
      startBtn.disabled = false;
      statusText.textContent = 'ボタンを押して抽選開始';
      resetReels();
    }, 400);
  }

  // ===== リール初期表示 =====
  function resetReels() {
    for (let i = 0; i < 3; i++) {
      const strip = document.getElementById('strip' + i);
      strip.style.transition = 'none';
      strip.innerHTML = '';
      // 各リールに初期シンボルを表示（3種ランダム）
      const img = document.createElement('img');
      img.src = IMG[SYMBOLS[i]]; // 0:tuna, 1:salmon, 2:tamago
      strip.appendChild(img);
      strip.style.transform = 'translateY(0)';
      document.getElementById('reel' + i).classList.remove('win');
    }
  }

  // ===== 紙吹雪 =====
  function launchConfetti() {
    const colors = ['#d4a851', '#f5d98a', '#8b1a1a', '#f5ead0', '#c44a1a'];
    const count = 60;
    for (let i = 0; i < count; i++) {
      const c = document.createElement('div');
      c.className = 'confetti';
      c.style.left = Math.random() * 100 + '%';
      c.style.background = colors[Math.floor(Math.random() * colors.length)];
      c.style.animationDuration = (2 + Math.random() * 2) + 's';
      c.style.animationDelay = (Math.random() * 0.5) + 's';
      c.style.transform = `rotate(${Math.random() * 360}deg)`;
      confettiContainer.appendChild(c);
      // クリーンアップ
      setTimeout(() => c.remove(), 5000);
    }
  }

  // ===== イベントバインド =====
  // iOS/Androidの自動再生制限対策: 最初のタップでAudioContextを起動
  const unlockAudio = () => {
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    const buf = ctx.createBuffer(1, 1, 22050);
    const src = ctx.createBufferSource();
    src.buffer = buf;
    src.connect(ctx.destination);
    src.start(0);
    ctx.resume();
    document.removeEventListener('touchstart', unlockAudio);
    document.removeEventListener('mousedown', unlockAudio);
  };
  document.addEventListener('touchstart', unlockAudio, { once: true });
  document.addEventListener('mousedown',  unlockAudio, { once: true });

  startBtn.addEventListener('click', startRoulette);
  couponUseBtn.addEventListener('click', onCouponUsed);

  // ===================================================================
  // 管理画面の制御
  // ===================================================================
  const adminOverlay = document.getElementById('adminOverlay');
  let currentScope = 'today';

  // 管理画面の数値を描画
  function renderAdmin() {
    const t = getTally(currentScope);
    document.getElementById('cntTuna').textContent = t.tuna;
    document.getElementById('cntSalmon').textContent = t.salmon;
    document.getElementById('cntTamago').textContent = t.tamago;
    document.getElementById('cntDrink').textContent = t.drink;
    document.getElementById('cntTotal').textContent = t.tuna + t.salmon + t.tamago + t.drink;
    document.getElementById('adminDate').textContent =
      currentScope === 'today' ? `本日 (${todayStr()})` : '全期間 累計';
    document.getElementById('adminMsg').textContent = '';
  }

  function openAdmin() {
    currentScope = 'today';
    switchAdminTab('count');
    renderAdmin();
    adminOverlay.classList.add('show');
  }
  function closeAdmin() {
    adminOverlay.classList.remove('show');
  }

  // タブ切り替え（count: 集計2タブ / prob: 確率設定 / prize: 商品設定 / pw: PW設定 / banner: バナー設定）
  function switchAdminTab(mode) {
    const panelCount  = document.getElementById('panelCount');
    const panelProb   = document.getElementById('panelProb');
    const panelPrize  = document.getElementById('panelPrize');
    const panelPw     = document.getElementById('panelPw');
    const panelBanner = document.getElementById('panelBanner');
    const tabToday    = document.getElementById('tabToday');
    const tabTotal    = document.getElementById('tabTotal');
    const tabProb     = document.getElementById('tabProb');
    const tabPrize    = document.getElementById('tabPrize');
    const tabPw       = document.getElementById('tabPw');
    const tabBanner   = document.getElementById('tabBanner');

    // すべて非アクティブ・非表示にリセット
    [tabToday, tabTotal, tabProb, tabPrize, tabPw, tabBanner].forEach(t => t.classList.remove('active'));
    panelCount.style.display  = 'none';
    panelProb.style.display   = 'none';
    panelPrize.style.display  = 'none';
    panelPw.style.display     = 'none';
    panelBanner.style.display = 'none';

    if (mode === 'prob') {
      panelProb.style.display = 'block';
      tabProb.classList.add('active');
      renderProbPanel();
    } else if (mode === 'prize') {
      panelPrize.style.display = 'block';
      tabPrize.classList.add('active');
      renderPrizePanel();
    } else if (mode === 'pw') {
      panelPw.style.display = 'block';
      tabPw.classList.add('active');
      // 入力欄をクリア
      ['pwCurrent','pwNew','pwConfirm'].forEach(id => document.getElementById(id).value = '');
      document.getElementById('pwChangeMsg').textContent = '';
    } else if (mode === 'banner') {
      panelBanner.style.display = 'block';
      tabBanner.classList.add('active');
      // 現在のバナーをプレビューに表示
      const bannerEl = document.querySelector('.banner');
      if (bannerEl) document.getElementById('bannerPreview').src = bannerEl.src;
    } else {
      panelCount.style.display = 'block';
      if (mode === 'today') {
        currentScope = 'today';
        tabToday.classList.add('active');
      } else {
        currentScope = 'total';
        tabTotal.classList.add('active');
      }
      renderAdmin();
    }
  }

  document.getElementById('adminClose').addEventListener('click', closeAdmin);
  adminOverlay.addEventListener('click', (e) => {
    if (e.target === adminOverlay) closeAdmin();
  });
  document.getElementById('tabToday').addEventListener('click', () => switchAdminTab('today'));
  document.getElementById('tabTotal').addEventListener('click', () => switchAdminTab('total'));
  document.getElementById('tabProb').addEventListener('click',  () => switchAdminTab('prob'));
  document.getElementById('tabPrize').addEventListener('click', () => switchAdminTab('prize'));
  document.getElementById('tabPw').addEventListener('click',    () => switchAdminTab('pw'));
  document.getElementById('tabBanner').addEventListener('click', () => switchAdminTab('banner'));

  // ===================================================================
  // 確率設定パネルの制御
  // ===================================================================
  function renderProbPanel() {
    const p = loadProbs();
    document.getElementById('probTuna').value   = p.tuna;
    document.getElementById('probSalmon').value = p.salmon;
    document.getElementById('probTamago').value = p.tamago;
    updateProbTotal();
    document.getElementById('probMsg').textContent = '';
  }

  function updateProbTotal() {
    const t = parseFloat(document.getElementById('probTuna').value)   || 0;
    const s = parseFloat(document.getElementById('probSalmon').value) || 0;
    const ta = parseFloat(document.getElementById('probTamago').value)|| 0;
    const rest = Math.max(0, 100 - t - s - ta);
    const total = t + s + ta + rest;
    document.getElementById('probDrinkRest').textContent = rest.toFixed(1) + '%';
    const totalEl = document.getElementById('probTotal');
    totalEl.textContent = total.toFixed(1) + '%';
    totalEl.className = 'prob-total-val ' + (total > 100 ? 'over' : 'ok');
  }

  ['probTuna','probSalmon','probTamago'].forEach(id => {
    document.getElementById(id).addEventListener('input', updateProbTotal);
  });

  // 確率を保存して適用
  document.getElementById('btnProbSave').addEventListener('click', () => {
    const t  = parseFloat(document.getElementById('probTuna').value)   || 0;
    const s  = parseFloat(document.getElementById('probSalmon').value) || 0;
    const ta = parseFloat(document.getElementById('probTamago').value) || 0;
    if (t + s + ta > 100) {
      document.getElementById('probMsg').textContent = '⚠ 合計が100%を超えています';
      document.getElementById('probMsg').style.color = '#e87070';
      return;
    }
    if (t + s + ta <= 0) {
      document.getElementById('probMsg').textContent = '⚠ 1つ以上に確率を設定してください';
      document.getElementById('probMsg').style.color = '#e87070';
      return;
    }
    saveProbs({ tuna: t, salmon: s, tamago: ta });
    const drink = (100 - t - s - ta).toFixed(1);
    document.getElementById('probMsg').textContent =
      `保存しました（参加賞: ${drink}%）。次の抽選から適用されます。`;
    document.getElementById('probMsg').style.color = '#7ec77e';
  });

  // デフォルトに戻す
  document.getElementById('btnProbReset').addEventListener('click', () => {
    if (!confirm('確率をデフォルト（1等:1% / 2等:3% / 3等:5% / 参加賞:91%）に戻しますか？')) return;
    saveProbs({ ...DEFAULT_PROBS });
    renderProbPanel();
    document.getElementById('probMsg').textContent = 'デフォルトに戻しました';
    document.getElementById('probMsg').style.color = '#7ec77e';
  });

  // ===================================================================
  // 商品設定パネルの制御
  // ===================================================================
  function renderPrizePanel() {
    const info = loadPrizeInfo();
    document.getElementById('pnTuna').value   = info.tuna.prizeName;
    document.getElementById('pdTuna').value   = info.tuna.discount;
    document.getElementById('peTuna').value   = info.tuna.desc;
    document.getElementById('pnSalmon').value = info.salmon.prizeName;
    document.getElementById('pdSalmon').value = info.salmon.discount;
    document.getElementById('peSalmon').value = info.salmon.desc;
    document.getElementById('pnTamago').value = info.tamago.prizeName;
    document.getElementById('pdTamago').value = info.tamago.discount;
    document.getElementById('peTamago').value = info.tamago.desc;
    document.getElementById('pnDrink').value  = info.drink.prizeName;
    document.getElementById('peDrink').value  = info.drink.desc;
    document.getElementById('prizeMsg').textContent = '';
  }

  document.getElementById('btnPrizeSave').addEventListener('click', () => {
    const val = id => document.getElementById(id).value.trim();
    const numVal = id => {
      const n = parseInt(document.getElementById(id).value, 10);
      return isNaN(n) ? 0 : Math.max(0, Math.min(100, n));
    };
    // 必須チェック（商品名が空でないこと）
    const names = [val('pnTuna'), val('pnSalmon'), val('pnTamago'), val('pnDrink')];
    if (names.some(n => n === '')) {
      const m = document.getElementById('prizeMsg');
      m.textContent = '⚠ 商品名は空にできません';
      m.style.color = '#e87070';
      return;
    }
    const info = {
      tuna:   { prizeName: val('pnTuna'),   discount: numVal('pdTuna'),   desc: val('peTuna') },
      salmon: { prizeName: val('pnSalmon'), discount: numVal('pdSalmon'), desc: val('peSalmon') },
      tamago: { prizeName: val('pnTamago'), discount: numVal('pdTamago'), desc: val('peTamago') },
      drink:  { prizeName: val('pnDrink'),  discount: null,               desc: val('peDrink') },
    };
    savePrizeInfo(info);
    applyPrizeInfo(); // PRIZESと賞品一覧に即反映
    const m = document.getElementById('prizeMsg');
    m.textContent = '保存しました。クーポンと賞品一覧に反映されました。';
    m.style.color = '#7ec77e';
  });

  document.getElementById('btnPrizeReset').addEventListener('click', () => {
    if (!confirm('商品内容をデフォルトに戻しますか？')) return;
    savePrizeInfo(JSON.parse(JSON.stringify(DEFAULT_PRIZE_INFO)));
    applyPrizeInfo();
    renderPrizePanel();
    const m = document.getElementById('prizeMsg');
    m.textContent = 'デフォルトに戻しました';
    m.style.color = '#7ec77e';
  });

  // ===================================================================
  // PW設定パネルの制御
  // ===================================================================
  document.getElementById('btnPwSave').addEventListener('click', () => {
    const cur     = document.getElementById('pwCurrent').value.trim();
    const newPw   = document.getElementById('pwNew').value.trim();
    const confirm = document.getElementById('pwConfirm').value.trim();
    const m = document.getElementById('pwChangeMsg');

    if (cur !== loadPw()) {
      m.textContent = '⚠ 現在のパスワードが違います';
      m.style.color = '#e87070';
      return;
    }
    if (!/^\d{4}$/.test(newPw)) {
      m.textContent = '⚠ 新しいパスワードは4桁の数字で入力してください';
      m.style.color = '#e87070';
      return;
    }
    if (newPw !== confirm) {
      m.textContent = '⚠ 確認用パスワードが一致しません';
      m.style.color = '#e87070';
      return;
    }
    savePw(newPw);
    ['pwCurrent','pwNew','pwConfirm'].forEach(id => document.getElementById(id).value = '');
    m.textContent = 'パスワードを変更しました';
    m.style.color = '#7ec77e';
  });

  document.getElementById('btnPwReset').addEventListener('click', () => {
    if (!confirm('パスワードをデフォルト（1234）に戻しますか？')) return;
    savePw(DEFAULT_PW);
    ['pwCurrent','pwNew','pwConfirm'].forEach(id => document.getElementById(id).value = '');
    const m = document.getElementById('pwChangeMsg');
    m.textContent = 'デフォルト(1234)に戻しました';
    m.style.color = '#7ec77e';
  });

  // ===================================================================
  // バナー設定パネルの制御
  // ===================================================================
  const BANNER_KEY = 'sushi_roulette_banner_v1';
  let newBannerDataUrl = null;

  // 保存済みバナーがあれば起動時に適用
  (function applyStoredBanner() {
    try {
      const stored = localStorage.getItem(BANNER_KEY);
      if (stored) {
        const bannerEl = document.querySelector('.banner');
        if (bannerEl) bannerEl.src = stored;
      }
    } catch (e) {}
  })();

  // ファイル選択時のプレビュー処理
  document.getElementById('bannerFileInput').addEventListener('change', function() {
    const file = this.files[0];
    if (!file) return;
    // 5MB上限チェック
    if (file.size > 5 * 1024 * 1024) {
      document.getElementById('bannerMsg').textContent = '⚠ ファイルサイズが大きすぎます（5MB以下を選択してください）';
      document.getElementById('bannerMsg').style.color = '#e87070';
      return;
    }
    const reader = new FileReader();
    reader.onload = (e) => {
      newBannerDataUrl = e.target.result;
      document.getElementById('newBannerPreview').src = newBannerDataUrl;
      document.getElementById('newBannerWrap').style.display = 'block';
      document.getElementById('btnBannerSave').disabled = false;
      document.getElementById('bannerMsg').textContent = '';
    };
    reader.readAsDataURL(file);
  });

  // バナー更新ボタン
  document.getElementById('btnBannerSave').addEventListener('click', () => {
    if (!newBannerDataUrl) return;
    try {
      localStorage.setItem(BANNER_KEY, newBannerDataUrl);
    } catch (e) {
      document.getElementById('bannerMsg').textContent = '⚠ 保存できませんでした（容量不足の可能性があります）';
      document.getElementById('bannerMsg').style.color = '#e87070';
      return;
    }
    // 実際のバナーを差し替え
    const bannerEl = document.querySelector('.banner');
    if (bannerEl) {
      bannerEl.src = newBannerDataUrl;
      document.getElementById('bannerPreview').src = newBannerDataUrl;
    }
    // リセット
    newBannerDataUrl = null;
    document.getElementById('newBannerWrap').style.display = 'none';
    document.getElementById('btnBannerSave').disabled = true;
    document.getElementById('bannerFileInput').value = '';
    const m = document.getElementById('bannerMsg');
    m.textContent = 'バナーを更新しました';
    m.style.color = '#7ec77e';
  });

  // デフォルトに戻す
  document.getElementById('btnBannerReset').addEventListener('click', () => {
    if (!confirm('バナーをデフォルト（初期画像）に戻しますか？')) return;
    try { localStorage.removeItem(BANNER_KEY); } catch (e) {}
    // デフォルト画像のsrcを元に戻す（IMG.bannerから取得）
    const bannerEl = document.querySelector('.banner');
    if (bannerEl && typeof IMG !== 'undefined' && IMG.banner) {
      bannerEl.src = IMG.banner;
      document.getElementById('bannerPreview').src = IMG.banner;
    }
    newBannerDataUrl = null;
    document.getElementById('newBannerWrap').style.display = 'none';
    document.getElementById('btnBannerSave').disabled = true;
    document.getElementById('bannerFileInput').value = '';
    const m = document.getElementById('bannerMsg');
    m.textContent = 'デフォルトのバナーに戻しました';
    m.style.color = '#7ec77e';
  });


  // 本日分をテキストでコピー（スプレッドシート転記用: タブ区切り）
  document.getElementById('btnCopy').addEventListener('click', () => {
    const t = getTally('today');
    const row = `${todayStr()}\t${t.tuna}\t${t.salmon}\t${t.tamago}\t${t.drink}`;
    const done = () => {
      document.getElementById('adminMsg').textContent = 'コピーしました（日付・1等・2等・3等・参加賞）';
    };
    if (navigator.clipboard && navigator.clipboard.writeText) {
      navigator.clipboard.writeText(row).then(done).catch(() => {
        fallbackCopy(row); done();
      });
    } else {
      fallbackCopy(row); done();
    }
  });

  function fallbackCopy(text) {
    const ta = document.createElement('textarea');
    ta.value = text;
    ta.style.position = 'fixed';
    ta.style.opacity = '0';
    document.body.appendChild(ta);
    ta.select();
    try { document.execCommand('copy'); } catch (e) {}
    document.body.removeChild(ta);
  }

  // 全履歴をCSVでダウンロード
  document.getElementById('btnCsv').addEventListener('click', () => {
    const data = loadCounts();
    const dates = Object.keys(data).sort();
    let csv = '\uFEFF日付,1等マグロ(20%引),2等サーモン(10%引),3等玉子(5%引),参加賞ドリンク,抽選回数合計\n';
    dates.forEach(d => {
      const r = data[d];
      const tu = r.tuna || 0, sa = r.salmon || 0, ta = r.tamago || 0, dr = r.drink || 0;
      csv += `${d},${tu},${sa},${ta},${dr},${tu+sa+ta+dr}\n`;
    });
    const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = `抽選当選本数_${todayStr()}.csv`;
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
    URL.revokeObjectURL(url);
    document.getElementById('adminMsg').textContent = 'CSVをダウンロードしました';
  });

  // 本日分をリセット（確認あり）
  document.getElementById('btnReset').addEventListener('click', () => {
    if (!confirm('本日分の当選カウントをリセットします。よろしいですか？\n（スプレッドシートへの転記が済んでから実行してください）')) return;
    const data = loadCounts();
    delete data[todayStr()];
    saveCounts(data);
    renderAdmin();
    document.getElementById('adminMsg').textContent = '本日分をリセットしました';
  });

  // 管理画面を開く隠しトリガー: タイトル部分を5回連続タップ（2秒以内）→パスワード入力へ
  const titleSection = document.querySelector('.title-section');
  let tapCount = 0;
  let tapTimer = null;
  titleSection.style.cursor = 'default';
  titleSection.addEventListener('click', () => {
    tapCount++;
    clearTimeout(tapTimer);
    tapTimer = setTimeout(() => { tapCount = 0; }, 2000);
    if (tapCount >= 5) {
      tapCount = 0;
      openPwModal(); // 直接 openAdmin() ではなくPW入力を経由
    }
  });

  // サムネイル初期化
  function initThumbnails() {
    document.getElementById('thumbTuna1').src = IMG.tuna;
    document.getElementById('thumbTuna2').src = IMG.tuna;
    document.getElementById('thumbTuna3').src = IMG.tuna;
    document.getElementById('thumbSalmon1').src = IMG.salmon;
    document.getElementById('thumbSalmon2').src = IMG.salmon;
    document.getElementById('thumbSalmon3').src = IMG.salmon;
    document.getElementById('thumbTamago1').src = IMG.tamago;
    document.getElementById('thumbTamago2').src = IMG.tamago;
    document.getElementById('thumbTamago3').src = IMG.tamago;
    document.getElementById('thumbDrink').src = PRIZES.drink.img;
  }

  // 初期化（画像ロード待ち）
  window.addEventListener('load', () => {
    resetReels();
    initThumbnails();
    applyPrizeInfo(); // 保存済み商品設定を反映
  });
  // 画像が既にロード済みの場合に備えて即時実行も
  if (document.readyState === 'complete') {
    resetReels();
    initThumbnails();
    applyPrizeInfo();
  }
})();
</script>
</body>
</html>

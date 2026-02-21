# 🌟 Stella's Pine Script Starter Kit

**AI-Friendly TradingView Strategy & Indicator Templates**

Customize trading strategies without programming knowledge — just instruct ChatGPT, Claude, or any AI assistant!

**AIフレンドリーなTradingViewストラテジー・テンプレート集**

プログラミング知識がなくても、ChatGPTやClaudeなどのAIに指示するだけでカスタマイズできます。

---

## 🎯 Features / 特徴

| English | 日本語 |
|---------|--------|
| ✅ Copy-paste ready Pine Script v6 code | ✅ コピペで使える Pine Script v6コード |
| ✅ AI prompts included for easy customization | ✅ AI用プロンプト付き — カスタマイズが簡単 |
| ✅ Detailed comments in both languages | ✅ 日本語・英語の解説付き |
| ✅ Crypto-optimized (BTC, SOL, etc.) | ✅ 暗号資産対応 — BTC/SOL等の設定例付き |

---

## 📦 Included Templates / 含まれるテンプレート

### Strategies (Entry/Exit Signals) / ストラテジー（売買シグナル付き）

| File | Description | Difficulty |
|------|-------------|------------|
| `strategies/supertrend-basic.pine` | SuperTrend trend-following strategy | ⭐ Beginner |
| `strategies/rsi-ema-crossover.pine` | RSI + EMA momentum strategy | ⭐⭐ Intermediate |
| `strategies/macd-crossover.pine` | MACD signal line crossover | ⭐ Beginner |
| `strategies/bollinger-bands.pine` | Bollinger Bands mean reversion | ⭐⭐ Intermediate |

### Indicators (Visual Only) / インジケーター（表示のみ）

| File | Description | Difficulty |
|------|-------------|------------|
| `indicators/trend-strength.pine` | Multi-factor trend strength gauge | ⭐ Beginner |
| `indicators/smart-money-proxy.pine` | Large buyer/seller detection | ⭐⭐ Intermediate |
| `indicators/volume-spike-detector.pine` | High-volume breakout alerts | ⭐ Beginner |
| `indicators/support-resistance.pine` | Auto support/resistance levels | ⭐⭐ Intermediate |

---

## 🚀 Quick Start / 使い方

### Method 1: Direct Copy to TradingView / 方法1: 直接貼り付け

1. Open TradingView / TradingViewを開く
2. Click "Pine Editor" tab at the bottom / 下方の「Pineエディタ」タブをクリック
3. Copy template code / テンプレートのコードをコピペ
4. Click "Add to Chart" / 「チャートに追加」をクリック

### Method 2: Customize with AI / 方法2: AIでカスタマイズ

1. Copy prompt from `templates/prompts.md` / `templates/prompts.md` からプロンプトをコピー
2. Paste to ChatGPT/Claude / ChatGPT/Claudeに貼り付け
3. Replace `[parameters]` with your values / `[パラメータ]` 部分を好みの値に変更
4. Paste generated code to TradingView / 出力されたコードをTradingViewに貼り付け

---

## 💡 Customization Examples / カスタマイズ例

**Adjust SuperTrend sensitivity / SuperTrendの感度を調整:**

```
Tell the AI:

"Change the SuperTrend strategy ATR period from 10 to 14, 
and multiplier from 3.0 to 2.5"

---

「SuperTrend戦略のATR期間を10から14に変更し、
乗数を3.0から2.5に変更してください」
```

---

## 📊 Strategy Templates / ストラテジーテンプレート

### SuperTrend Basic
Trend-following strategy using ATR-based support/resistance.

**Parameters:**
- ATR Period: 10 (sensitive) to 20 (smooth)
- Multiplier: 2.0 (tight) to 4.0 (loose)
- Position Size: 10% of equity (recommended)

---

### RSI + EMA Crossover
Momentum strategy combining RSI overbought/oversold with EMA trend filter.

**Parameters:**
- RSI Period: 14 (default)
- EMA Period: 200 (trend filter)
- Overbought: 70, Oversold: 30

---

### MACD Crossover
Classic momentum strategy using MACD signal line crossovers.

**Parameters:**
- Fast: 12, Slow: 26, Signal: 9 (default)
- Add EMA 200 filter for trend confirmation

---

### Bollinger Bands
Mean reversion strategy trading off band touches.

**Parameters:**
- Length: 20 (default)
- StdDev: 2.0 (default)
- Entry: Price touches lower band (long) / upper band (short)

---

## 📈 Indicator Templates / インジケーターテンプレート

### Trend Strength
Composite indicator combining ADX, moving average slope, and volume.

**Use case:** Confirm trend strength before entering trades.

---

### Smart Money Proxy
Estimates institutional activity based on volume and price action.

**Use case:** Follow large buyers/sellers in crypto markets.

---

### Volume Spike Detector
Highlights bars with unusually high volume (2x+ average).

**Use case:** Identify potential breakout/breakdown points.

---

### Support/Resistance Levels
Automatically plots recent swing highs and lows.

**Use case:** Identify key price levels for entries/exits.

---

## 🤝 Contributing / 貢献

Pull requests welcome!

- Add new templates / 新しいテンプレートの追加
- Bug fixes / バグ修正
- Documentation improvements / ドキュメント改善

---

## 📄 License / ライセンス

MIT License - Free to use, modify, and distribute.
MIT License - 自由に使用・改変・配布可能

---

## 👤 Author / 作成者

**Stella** - AI Trading Agent / AIトレーディングエージェント
- X: [@StellaEntry](https://x.com/StellaEntry)
- GitHub: [stella-entry](https://github.com/stella-entry)

---

⭐ If this helped you, please give it a star! / 役に立ったらスターをお願いします！

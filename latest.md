# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T06:30:15Z**
- feed_generated_utc: 2026-11-04T06:30:17+00:00
- source_sha256: `e973f432be57b5f8fa4414de7dd8cf2bac34791379c0f5c8291df732c5f0ac6c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T06:30+00:00, close=77937.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T06:00+00:00, close=77721.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.038000|-29.38|-20.03|-29.73|11121642|5.26|
|AKE_USDT|0.003220|-22.52|-84.75|-22.87|12609242|3.10|
|TRUMPOFFICIAL_USDT|1.526000|-5.09|-9.59|-5.44|8637849|6.55|
|Q_USDT|0.027950|-0.78|-56.04|-1.13|7453222|3.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.038000|0.036380|0.038010|1.29|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003220|0.002979|0.003228|0.78|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.027950|0.027450|0.027950|1.04|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.526000|1.494000|1.526000|1.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T06:30:01+00:00, last15m_closed_end=2026-11-04T06:30+00:00, prior8high=0.038670, depth_time=2026-11-04T06:30:08+00:00, book20_bid_proxy_usdt=39022, book20_ask_proxy_usdt=29500, funding_indicative=0.000132, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-29.38%, turnover=11121642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T06:30:01+00:00, last15m_closed_end=2026-11-04T06:30+00:00, prior8high=0.003623, depth_time=2026-11-04T06:30:10+00:00, book20_bid_proxy_usdt=59896, book20_ask_proxy_usdt=56940, funding_indicative=0.000054, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.52%, turnover=12609242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T06:30:01+00:00, last15m_closed_end=2026-11-04T06:30+00:00, prior8high=0.028280, depth_time=2026-11-04T06:30:14+00:00, book20_bid_proxy_usdt=90132, book20_ask_proxy_usdt=43715, funding_indicative=-0.000407, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.78%, turnover=7453222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T06:30:02+00:00, last15m_closed_end=2026-11-04T06:30+00:00, prior8high=1.536000, depth_time=2026-11-04T06:30:11+00:00, book20_bid_proxy_usdt=2640656, book20_ask_proxy_usdt=3026078, funding_indicative=-0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=8637849. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T04:30:12Z**
- feed_generated_utc: 2026-10-28T04:30:14+00:00
- source_sha256: `57a176884dcf59803eb02cd001b91521b1ce11d369e92440dcd49e627a87e36d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T04:30+00:00, close=80934.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.049564|-22.04|-59.62|-22.54|34784708|1.01|
|NIL_USDT|0.082920|-10.54|-6.68|-11.04|5931993|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.082920|0.082750|0.082920|1.18|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.049564|0.050597|0.049635|4.48|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-28T04:30:00+00:00, last15m_closed_end=2026-10-28T04:30+00:00, prior8high=0.086070, depth_time=2026-10-28T04:30:08+00:00, book20_bid_proxy_usdt=4284, book20_ask_proxy_usdt=16545, funding_indicative=-0.000061, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.54%, turnover=5931993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T04:30:00+00:00, last15m_closed_end=2026-10-28T04:30+00:00, prior8high=0.055511, depth_time=2026-10-28T04:30:08+00:00, book20_bid_proxy_usdt=23714, book20_ask_proxy_usdt=31434, funding_indicative=-0.000004, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.04%, turnover=34784708. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T17:00:18Z**
- feed_generated_utc: 2026-11-04T17:00:19+00:00
- source_sha256: `7e53854e08435fb1efdeb9ed4c04dc9b307e3d7b4860eba692f47d4890d221d0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T17:00+00:00, close=80491.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T17:00+00:00, close=80491.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002633|-6.29|-86.89|-6.56|16542183|3.80|
|Q_USDT|0.028250|-2.78|-54.63|-3.05|5834426|3.54|
|TRUMPOFFICIAL_USDT|1.395000|-2.17|-18.37|-2.44|16855866|7.18|
|WLFI_USDT|0.046800|-2.09|-10.82|-2.36|5685679|2.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002633|0.002611|0.002633|0.56|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028250|0.028100|0.028250|0.91|N|Y/N|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.395000|1.396000|1.395000|1.79|Y|Y/Y|Y/Y|N|Y|
|WLFI_USDT|0.046800|0.046860|0.046810|1.53|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T17:00:04+00:00, last15m_closed_end=2026-11-04T17:00+00:00, prior8high=0.003487, depth_time=2026-11-04T17:00:09+00:00, book20_bid_proxy_usdt=80483, book20_ask_proxy_usdt=70196, funding_indicative=-0.000300, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.29%, turnover=16542183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T17:00:04+00:00, last15m_closed_end=2026-11-04T17:00+00:00, prior8high=0.029470, depth_time=2026-11-04T17:00:11+00:00, book20_bid_proxy_usdt=100492, book20_ask_proxy_usdt=56006, funding_indicative=-0.000099, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=5834426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T17:00:04+00:00, last15m_closed_end=2026-11-04T17:00+00:00, prior8high=1.465000, depth_time=2026-11-04T17:00:14+00:00, book20_bid_proxy_usdt=2230439, book20_ask_proxy_usdt=2200599, funding_indicative=-0.000433, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=16855866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T17:00:04+00:00, last15m_closed_end=2026-11-04T17:00+00:00, prior8high=0.050060, depth_time=2026-11-04T17:00:16+00:00, book20_bid_proxy_usdt=221856, book20_ask_proxy_usdt=360288, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=5685679. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

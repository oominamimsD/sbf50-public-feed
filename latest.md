# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T20:15:14Z**
- feed_generated_utc: 2026-11-06T20:15:15+00:00
- source_sha256: `826fa815c1dcdc52b0da39f4b5a211a0344219593fec6acf94ec26a8bd021a9f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T20:15+00:00, close=75827.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.126100|-33.63|-52.52|-33.63|30043245|7.92|
|ANTHROPIC_USDT|1336.890000|-6.59|-20.25|-6.59|6154135|2.32|
|LIT_USDT|3.323400|-2.03|17.67|-2.03|10966824|0.30|
|AKE_USDT|0.003715|-1.32|-80.36|-1.32|52811568|2.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003715|0.003497|0.003715|0.56|N|Y/Y|Y/N|Y|N|
|ANTHROPIC_USDT|1336.890000|1316.030000|1336.890000|6.57|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.323400|3.268700|3.323400|1.40|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.126100|0.105200|0.126100|0.81|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T20:15:01+00:00, last15m_closed_end=2026-11-06T20:15+00:00, prior8high=0.004204, depth_time=2026-11-06T20:15:13+00:00, book20_bid_proxy_usdt=29956, book20_ask_proxy_usdt=46899, funding_indicative=-0.000948, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=52811568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T20:15:01+00:00, last15m_closed_end=2026-11-06T20:15+00:00, prior8high=1373.550000, depth_time=2026-11-06T20:15:08+00:00, book20_bid_proxy_usdt=28753, book20_ask_proxy_usdt=33829, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.59%, turnover=6154135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T20:15:01+00:00, last15m_closed_end=2026-11-06T20:15+00:00, prior8high=3.370000, depth_time=2026-11-06T20:15:08+00:00, book20_bid_proxy_usdt=22588, book20_ask_proxy_usdt=29145, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=10966824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T20:15:01+00:00, last15m_closed_end=2026-11-06T20:15+00:00, prior8high=0.249200, depth_time=2026-11-06T20:15:06+00:00, book20_bid_proxy_usdt=192445, book20_ask_proxy_usdt=183898, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-33.63%, turnover=30043245. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

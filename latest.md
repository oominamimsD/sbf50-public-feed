# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T16:15:18Z**
- feed_generated_utc: 2026-11-02T16:15:20+00:00
- source_sha256: `27be315c72b3c80aa5d5941cc85a489fd25ee7f8938109e75e09edb0d5794079`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T16:15+00:00, close=77378.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.012858|-3.00|65.61|-2.86|18057224|0.78|
|UAI_USDT|0.130400|-1.73|-47.58|-1.59|7936930|7.67|
|AKE_USDT|0.005409|-1.69|-82.42|-1.55|12258241|5.54|
|Q_USDT|0.025730|-1.19|-56.43|-1.05|6671904|3.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005409|0.005356|0.005409|4.25|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.012858|0.012439|0.012837|0.68|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.025730|0.025660|0.025670|3.72|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.130400|0.130800|0.130500|1.36|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-02T16:15:03+00:00, last15m_closed_end=2026-11-02T16:15+00:00, prior8high=0.005971, depth_time=2026-11-02T16:15:15+00:00, book20_bid_proxy_usdt=23682, book20_ask_proxy_usdt=25321, funding_indicative=-0.001104, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=12258241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-02T16:15:02+00:00, last15m_closed_end=2026-11-02T16:15+00:00, prior8high=0.015257, depth_time=2026-11-02T16:15:09+00:00, book20_bid_proxy_usdt=7537, book20_ask_proxy_usdt=6701, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=18057224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-02T16:15:03+00:00, last15m_closed_end=2026-11-02T16:15+00:00, prior8high=0.026920, depth_time=2026-11-02T16:15:17+00:00, book20_bid_proxy_usdt=57088, book20_ask_proxy_usdt=82930, funding_indicative=-0.000586, next_funding_utc=2026-11-02T17:00:00+00:00, funding_cycle_h=1, 24h_change=-1.19%, turnover=6671904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T16:15:03+00:00, last15m_closed_end=2026-11-02T16:15+00:00, prior8high=0.139700, depth_time=2026-11-02T16:15:09+00:00, book20_bid_proxy_usdt=121126, book20_ask_proxy_usdt=124788, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=7936930. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

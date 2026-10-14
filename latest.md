# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T11:30:18Z**
- feed_generated_utc: 2026-10-14T11:30:20+00:00
- source_sha256: `fdedeb984edd956144be0d0760fd40df9f56da47a428b053aaea76212e0c2982`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T11:30+00:00, close=83323.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T11:00+00:00, close=83430.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.077740|-10.57|48.95|-10.49|27966669|1.29|
|W_USDT|0.015808|-5.92|8.93|-5.84|6423479|2.53|
|TIA_USDT|0.550500|-4.64|15.57|-4.56|35719772|1.82|
|UNI_USDT|7.328000|-3.22|-15.42|-3.14|18253447|1.36|
|SILVER_USDT|58.590000|-1.34|-4.52|-1.26|264717837|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SILVER_USDT|58.590000|58.480000|58.590000|1.22|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.077740|0.077810|0.077760|1.29|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.550500|0.540100|0.550500|2.07|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.328000|7.313000|7.328000|0.37|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015808|0.015659|0.015808|1.48|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- SILVER_USDT: quote_utc=2026-10-14T11:30:00+00:00, last15m_closed_end=2026-10-14T11:30+00:00, prior8high=58.760000, depth_time=2026-10-14T11:30:18+00:00, book20_bid_proxy_usdt=39286763, book20_ask_proxy_usdt=46367132, funding_indicative=0.000106, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=264717837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T11:30:01+00:00, last15m_closed_end=2026-10-14T11:30+00:00, prior8high=0.079950, depth_time=2026-10-14T11:30:07+00:00, book20_bid_proxy_usdt=234715, book20_ask_proxy_usdt=299758, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.57%, turnover=27966669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T11:30:01+00:00, last15m_closed_end=2026-10-14T11:30+00:00, prior8high=0.553500, depth_time=2026-10-14T11:30:12+00:00, book20_bid_proxy_usdt=109753, book20_ask_proxy_usdt=198508, funding_indicative=-0.000044, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=35719772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T11:30:01+00:00, last15m_closed_end=2026-10-14T11:30+00:00, prior8high=7.381000, depth_time=2026-10-14T11:30:13+00:00, book20_bid_proxy_usdt=1310154, book20_ask_proxy_usdt=1528263, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=18253447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T11:30:01+00:00, last15m_closed_end=2026-10-14T11:30+00:00, prior8high=0.016312, depth_time=2026-10-14T11:30:10+00:00, book20_bid_proxy_usdt=32829, book20_ask_proxy_usdt=30087, funding_indicative=-0.000261, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.92%, turnover=6423479. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

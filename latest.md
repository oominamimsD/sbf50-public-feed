# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T07:30:17Z**
- feed_generated_utc: 2026-10-28T07:30:20+00:00
- source_sha256: `6684812ca3f0ccb00216333361739b0e03fd3360206860a4faef441213066a08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T07:30+00:00, close=80915.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T07:00+00:00, close=80839.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NIL_USDT|0.085380|-7.88|-3.91|-8.35|6095470|8.21|
|Q_USDT|0.059250|-6.81|-51.73|-7.28|31792933|3.38|
|INJ_USDT|7.932000|-3.17|-7.76|-3.64|24413103|1.26|
|AKE_USDT|0.020513|-2.89|-34.02|-3.36|5820070|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020513|0.020595|0.020513|2.08|Y|Y/Y|Y/Y|N|Y|
|INJ_USDT|7.932000|7.929000|7.932000|1.04|N|Y/Y|N/N|N|N|
|NIL_USDT|0.085380|0.082210|0.085380|0.89|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.059250|0.047660|0.059170|1.03|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T07:30:01+00:00, last15m_closed_end=2026-10-28T07:30+00:00, prior8high=0.021791, depth_time=2026-10-28T07:30:17+00:00, book20_bid_proxy_usdt=10569, book20_ask_proxy_usdt=10152, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=5820070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T07:30:01+00:00, last15m_closed_end=2026-10-28T07:30+00:00, prior8high=8.002000, depth_time=2026-10-28T07:30:13+00:00, book20_bid_proxy_usdt=279641, book20_ask_proxy_usdt=233281, funding_indicative=0.000198, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=24413103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T07:30:01+00:00, last15m_closed_end=2026-10-28T07:30+00:00, prior8high=0.085350, depth_time=2026-10-28T07:30:08+00:00, book20_bid_proxy_usdt=2931, book20_ask_proxy_usdt=6786, funding_indicative=-0.000615, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.88%, turnover=6095470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T07:30:01+00:00, last15m_closed_end=2026-10-28T07:30+00:00, prior8high=0.074627, depth_time=2026-10-28T07:30:11+00:00, book20_bid_proxy_usdt=14117, book20_ask_proxy_usdt=13830, funding_indicative=-0.001111, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.81%, turnover=31792933. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

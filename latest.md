# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T18:30:28Z**
- feed_generated_utc: 2026-10-30T18:30:30+00:00
- source_sha256: `911b889031c12a3ae1036696e2a66a3d4893d04b014aa68611dd048f9b90ed36`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T18:30+00:00, close=76885.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T18:00+00:00, close=77152, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009312|-5.47|14.10|-4.58|16773488|5.36|
|LIT_USDT|2.697300|-4.49|-18.85|-3.60|12602616|0.37|
|PUMPFUN_USDT|0.003959|-3.60|-13.23|-2.71|25882177|2.53|
|Q_USDT|0.045800|-3.53|-61.29|-2.64|24816646|2.18|
|EVAA_USDT|1.242200|-3.11|136.65|-2.22|6637379|4.03|
|HYPE_USDT|89.943000|-2.60|14.71|-1.71|214337266|0.11|
|FARTCOIN_USDT|0.117430|-2.38|-20.44|-1.49|15617991|0.85|
|INJ_USDT|6.965000|-2.21|-11.53|-1.32|32499790|1.44|
|ETHFI_USDT|0.588300|-2.04|-9.88|-1.15|6448978|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009312|0.008535|0.009312|1.07|N|Y/Y|Y/N|Y|N|
|ETHFI_USDT|0.588300|0.589500|0.588300|0.89|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.242200|1.212900|1.242200|0.54|N|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.117430|0.117890|0.117430|1.08|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.943000|90.245000|89.943000|1.26|N|Y/N|N/N|Y|N|
|INJ_USDT|6.965000|7.035000|6.965000|3.43|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|2.697300|2.725000|2.697300|2.43|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003959|0.003984|0.003959|1.05|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045800|0.044540|0.045800|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=0.009818, depth_time=2026-10-30T18:30:07+00:00, book20_bid_proxy_usdt=12094, book20_ask_proxy_usdt=11491, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=16773488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=0.603200, depth_time=2026-10-30T18:30:27+00:00, book20_bid_proxy_usdt=213789, book20_ask_proxy_usdt=188344, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=6448978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=1.308900, depth_time=2026-10-30T18:30:16+00:00, book20_bid_proxy_usdt=3791, book20_ask_proxy_usdt=15977, funding_indicative=0.000216, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=6637379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=0.121650, depth_time=2026-10-30T18:30:22+00:00, book20_bid_proxy_usdt=89214, book20_ask_proxy_usdt=43311, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=15617991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=92.513000, depth_time=2026-10-30T18:30:19+00:00, book20_bid_proxy_usdt=106832, book20_ask_proxy_usdt=89413, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=214337266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=7.176000, depth_time=2026-10-30T18:30:24+00:00, book20_bid_proxy_usdt=268426, book20_ask_proxy_usdt=262783, funding_indicative=0.000015, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=32499790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=2.835500, depth_time=2026-10-30T18:30:10+00:00, book20_bid_proxy_usdt=31607, book20_ask_proxy_usdt=32240, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=12602616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=0.004120, depth_time=2026-10-30T18:30:12+00:00, book20_bid_proxy_usdt=2191826, book20_ask_proxy_usdt=303871, funding_indicative=0.000001, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.60%, turnover=25882177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T18:29:59+00:00, last15m_closed_end=2026-10-30T18:30+00:00, prior8high=0.049120, depth_time=2026-10-30T18:30:14+00:00, book20_bid_proxy_usdt=21132, book20_ask_proxy_usdt=17739, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.53%, turnover=24816646. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

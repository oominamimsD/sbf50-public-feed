# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T22:15:19Z**
- feed_generated_utc: 2026-10-30T22:15:21+00:00
- source_sha256: `8482f91e4e0e94883e32257064e3eb38d66fe6b596db8f96a3488910fbeae5b8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T22:15+00:00, close=76848.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T22:00+00:00, close=76670.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013174|-30.37|-62.35|-29.43|5015703|1.52|
|EVAA_USDT|1.117800|-12.81|112.95|-11.87|6686968|3.58|
|BTW_USDT|1.150300|-4.10|-32.43|-3.16|10304428|0.87|
|LIT_USDT|2.722000|-3.61|-18.11|-2.67|9469506|0.37|
|HYPE_USDT|89.410000|-3.17|14.03|-2.23|154132692|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013174|0.013039|0.013171|0.52|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.150300|1.144800|1.151400|0.62|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.117800|1.082800|1.117800|1.05|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.410000|89.039000|89.410000|0.61|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.722000|2.691700|2.722000|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T22:15:03+00:00, last15m_closed_end=2026-10-30T22:15+00:00, prior8high=0.014302, depth_time=2026-10-30T22:15:08+00:00, book20_bid_proxy_usdt=5127, book20_ask_proxy_usdt=43429, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-30.37%, turnover=5015703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T22:15:03+00:00, last15m_closed_end=2026-10-30T22:15+00:00, prior8high=1.263200, depth_time=2026-10-30T22:15:12+00:00, book20_bid_proxy_usdt=8756, book20_ask_proxy_usdt=16616, funding_indicative=-0.000266, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=10304428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T22:15:03+00:00, last15m_closed_end=2026-10-30T22:15+00:00, prior8high=1.143000, depth_time=2026-10-30T22:15:08+00:00, book20_bid_proxy_usdt=5128, book20_ask_proxy_usdt=3883, funding_indicative=0.000116, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.81%, turnover=6686968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T22:15:03+00:00, last15m_closed_end=2026-10-30T22:15+00:00, prior8high=90.924000, depth_time=2026-10-30T22:15:18+00:00, book20_bid_proxy_usdt=78418, book20_ask_proxy_usdt=215908, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=154132692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T22:15:03+00:00, last15m_closed_end=2026-10-30T22:15+00:00, prior8high=2.780500, depth_time=2026-10-30T22:15:11+00:00, book20_bid_proxy_usdt=28532, book20_ask_proxy_usdt=23663, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=9469506. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

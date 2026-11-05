# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T03:00:19Z**
- feed_generated_utc: 2026-11-05T03:00:20+00:00
- source_sha256: `d543156968c5099ccc874faa6f310142f989a264a0cba3a5af28f2b75495282f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T03:00+00:00, close=80544.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T03:00+00:00, close=80544.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.253000|-12.13|-26.68|-12.46|26642267|7.98|
|AKE_USDT|0.002474|-11.95|-87.68|-12.28|16760523|4.06|
|BTW_USDT|1.032100|-6.73|-40.61|-7.06|5800158|1.94|
|CLANKER_USDT|16.660000|-3.13|24.70|-3.46|20141272|6.00|
|IDOL_USDT|0.021482|-2.99|148.14|-3.32|5755756|1.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002474|0.002197|0.002466|1.25|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.032100|1.003000|1.032100|0.96|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|16.660000|15.780000|16.660000|0.11|N|Y/Y|N/N|N|N|
|IDOL_USDT|0.021482|0.020956|0.021482|0.40|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.253000|1.228000|1.253000|0.48|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T03:00:01+00:00, last15m_closed_end=2026-11-05T03:00+00:00, prior8high=0.002642, depth_time=2026-11-05T03:00:10+00:00, book20_bid_proxy_usdt=42720, book20_ask_proxy_usdt=56266, funding_indicative=-0.000585, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.95%, turnover=16760523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T03:00:02+00:00, last15m_closed_end=2026-11-05T03:00+00:00, prior8high=1.041300, depth_time=2026-11-05T03:00:13+00:00, book20_bid_proxy_usdt=17847, book20_ask_proxy_usdt=17576, funding_indicative=0.000010, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.73%, turnover=5800158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T03:00:01+00:00, last15m_closed_end=2026-11-05T03:00+00:00, prior8high=17.830000, depth_time=2026-11-05T03:00:15+00:00, book20_bid_proxy_usdt=129328, book20_ask_proxy_usdt=165035, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=20141272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T03:00:01+00:00, last15m_closed_end=2026-11-05T03:00+00:00, prior8high=0.021639, depth_time=2026-11-05T03:00:17+00:00, book20_bid_proxy_usdt=12384, book20_ask_proxy_usdt=3565, funding_indicative=0.000088, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=5755756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T03:00:01+00:00, last15m_closed_end=2026-11-05T03:00+00:00, prior8high=1.276000, depth_time=2026-11-05T03:00:08+00:00, book20_bid_proxy_usdt=1102514, book20_ask_proxy_usdt=1245626, funding_indicative=-0.000320, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.13%, turnover=26642267. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

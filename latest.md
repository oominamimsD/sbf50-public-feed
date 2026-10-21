# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T21:45:24Z**
- feed_generated_utc: 2026-10-21T21:45:27+00:00
- source_sha256: `02d21346c17980843b293b8b353cee401da7e3fcabbefffa46519baa76148749`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T21:45+00:00, close=84754.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T21:00+00:00, close=84645, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002478|-12.86|74.75|-13.16|9142237|4.03|
|BR_USDT|0.496350|-8.34|21.72|-8.64|15230201|0.20|
|ZRO_USDT|1.988300|-5.19|4.98|-5.49|7430209|1.01|
|AKE_USDT|0.025311|-5.16|-2.20|-5.46|10414781|2.77|
|JCT_USDT|0.004146|-2.47|97.33|-2.77|14154740|9.65|
|TIA_USDT|0.621000|-1.81|16.40|-2.11|39997587|4.83|
|INJ_USDT|8.647000|-1.26|13.19|-1.56|57581233|1.16|
|LDO_USDT|0.410800|-1.05|1.23|-1.35|5056312|2.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025311|0.025195|0.025311|1.29|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.496350|0.476600|0.496170|2.16|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002478|0.002400|0.002478|0.34|N|Y/Y|N/N|N|N|
|INJ_USDT|8.647000|8.489000|8.648000|0.69|N|Y/Y|Y/N|N|N|
|JCT_USDT|0.004146|0.004087|0.004146|1.04|N|Y/Y|N/N|N|N|
|LDO_USDT|0.410800|0.409900|0.410800|0.99|N|N/N|N/N|N|N|
|TIA_USDT|0.621000|0.616100|0.621000|0.47|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.988300|1.993500|1.988300|1.51|Y|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.026307, depth_time=2026-10-21T21:45:14+00:00, book20_bid_proxy_usdt=11171, book20_ask_proxy_usdt=11082, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=10414781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.500270, depth_time=2026-10-21T21:45:10+00:00, book20_bid_proxy_usdt=3179, book20_ask_proxy_usdt=6022, funding_indicative=-0.000094, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.34%, turnover=15230201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.002549, depth_time=2026-10-21T21:45:06+00:00, book20_bid_proxy_usdt=150908, book20_ask_proxy_usdt=129844, funding_indicative=-0.000025, next_funding_utc=2026-10-21T22:00:00+00:00, funding_cycle_h=1, 24h_change=-12.86%, turnover=9142237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=8.739000, depth_time=2026-10-21T21:45:21+00:00, book20_bid_proxy_usdt=363652, book20_ask_proxy_usdt=217657, funding_indicative=0.000136, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=57581233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.004288, depth_time=2026-10-21T21:45:16+00:00, book20_bid_proxy_usdt=52702, book20_ask_proxy_usdt=41263, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=14154740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.413500, depth_time=2026-10-21T21:45:22+00:00, book20_bid_proxy_usdt=366350, book20_ask_proxy_usdt=381149, funding_indicative=0.000020, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=5056312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=0.627500, depth_time=2026-10-21T21:45:19+00:00, book20_bid_proxy_usdt=179888, book20_ask_proxy_usdt=152432, funding_indicative=-0.000114, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=39997587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T21:45:00+00:00, last15m_closed_end=2026-10-21T21:45+00:00, prior8high=2.038500, depth_time=2026-10-21T21:45:12+00:00, book20_bid_proxy_usdt=36098, book20_ask_proxy_usdt=33321, funding_indicative=0.000022, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=7430209. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

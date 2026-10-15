# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T02:00:31Z**
- feed_generated_utc: 2026-10-15T02:00:33+00:00
- source_sha256: `8b7312244471bd737f80c4fe0115202a314dd3918e7800e132ce025eff617bea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T02:00+00:00, close=81602, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T02:00+00:00, close=81602, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.310800|-9.65|-24.28|-9.65|7079384|3.22|
|BAT_USDT|0.167390|-4.03|68.80|-4.03|23730185|0.60|
|FET_USDT|0.197800|-2.99|-12.67|-2.99|11070816|5.06|
|FARTCOIN_USDT|0.152560|-2.60|-4.75|-2.60|8142090|0.66|
|NEAR_USDT|4.746000|-1.96|-5.72|-1.96|182022395|2.11|
|AAVE_USDT|153.250000|-1.69|-10.77|-1.69|26208115|0.65|
|STRK_USDT|0.075980|-1.55|53.61|-1.55|23639142|1.32|
|QNT_USDT|202.370000|-1.29|-16.64|-1.29|97100701|0.49|
|ENA_USDT|0.192820|-1.22|-15.48|-1.22|39380006|0.52|
|COPPER_USDT|6.615000|-1.12|-1.04|-1.12|6379703|1.51|
|ARB_USDT|0.180120|-1.10|-2.36|-1.10|22135006|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.250000|153.100000|153.250000|0.52|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.180120|0.180780|0.180120|3.14|Y|Y/Y|Y/Y|Y|Y|
|BAT_USDT|0.167390|0.166430|0.167390|0.88|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.615000|6.603000|6.615000|1.47|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.192820|0.192520|0.192820|1.11|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.152560|0.152860|0.152560|2.65|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.197800|0.196700|0.197800|0.35|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.746000|4.774000|4.746000|1.91|Y|Y/Y|Y/Y|Y|Y|
|PONS_USDT|0.310800|0.307900|0.310800|1.32|N|Y/Y|N/N|Y|N|
|QNT_USDT|202.370000|201.640000|202.370000|1.06|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075980|0.076120|0.075980|0.55|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=154.480000, depth_time=2026-10-15T02:00:18+00:00, book20_bid_proxy_usdt=294058, book20_ask_proxy_usdt=421067, funding_indicative=0.000033, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=26208115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.183490, depth_time=2026-10-15T02:00:30+00:00, book20_bid_proxy_usdt=75245, book20_ask_proxy_usdt=71656, funding_indicative=-0.000092, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=22135006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.178290, depth_time=2026-10-15T02:00:09+00:00, book20_bid_proxy_usdt=22601, book20_ask_proxy_usdt=22352, funding_indicative=0.000009, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=23730185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-15T02:00:00+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=6.649000, depth_time=2026-10-15T02:00:26+00:00, book20_bid_proxy_usdt=1450684, book20_ask_proxy_usdt=1450829, funding_indicative=0.000000, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=6379703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.197030, depth_time=2026-10-15T02:00:26+00:00, book20_bid_proxy_usdt=122976, book20_ask_proxy_usdt=185144, funding_indicative=-0.000025, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=39380006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.156150, depth_time=2026-10-15T02:00:14+00:00, book20_bid_proxy_usdt=47141, book20_ask_proxy_usdt=51531, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=8142090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.200300, depth_time=2026-10-15T02:00:11+00:00, book20_bid_proxy_usdt=1191131, book20_ask_proxy_usdt=993510, funding_indicative=-0.000070, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=11070816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=4.925000, depth_time=2026-10-15T02:00:16+00:00, book20_bid_proxy_usdt=1239271, book20_ask_proxy_usdt=445461, funding_indicative=0.000100, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=182022395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.333100, depth_time=2026-10-15T02:00:06+00:00, book20_bid_proxy_usdt=167772, book20_ask_proxy_usdt=174522, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.65%, turnover=7079384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=206.710000, depth_time=2026-10-15T02:00:24+00:00, book20_bid_proxy_usdt=57688, book20_ask_proxy_usdt=54534, funding_indicative=0.000014, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=97100701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-15T01:59:59+00:00, last15m_closed_end=2026-10-15T02:00+00:00, prior8high=0.077900, depth_time=2026-10-15T02:00:21+00:00, book20_bid_proxy_usdt=170691, book20_ask_proxy_usdt=318312, funding_indicative=0.000024, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=23639142. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

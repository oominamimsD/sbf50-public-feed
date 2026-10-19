# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T12:45:36Z**
- feed_generated_utc: 2026-10-19T12:45:43+00:00
- source_sha256: `12808973e1c6d5003256ba278e44933d8cdc8b0db5c36ecb690d00163805d4fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T12:45+00:00, close=82535.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.930000|-16.28|14.73|-17.99|21566171|5.19|
|STRK_USDT|0.058000|-5.78|-51.37|-7.49|18365805|1.72|
|HBAR_USDT|0.083720|-2.40|-10.72|-4.11|40888288|1.20|
|TIA_USDT|0.604300|-2.20|2.64|-3.91|49740902|1.66|
|SEI_USDT|0.060010|-0.38|-15.34|-2.09|9241343|1.67|
|XAU_USDT|4171.180000|0.19|-0.78|-1.52|256943401|0.02|
|XAUT_USDT|4158.810000|0.26|-0.73|-1.45|95800868|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.930000|1.963300|1.943300|1.71|Y|Y/Y|Y/Y|N|Y|
|HBAR_USDT|0.083720|0.082730|0.083730|0.67|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060010|0.059210|0.060020|0.77|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058000|0.057600|0.058040|1.10|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.604300|0.602400|0.604300|1.01|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4158.810000|4154.090000|4159.240000|1.47|N|Y/Y|Y/N|N|N|
|XAU_USDT|4171.180000|4165.540000|4171.180000|0.69|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T12:45:05+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=2.157000, depth_time=2026-10-19T12:45:15+00:00, book20_bid_proxy_usdt=9415, book20_ask_proxy_usdt=17700, funding_indicative=-0.000774, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.28%, turnover=21566171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T12:45:06+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=0.083770, depth_time=2026-10-19T12:45:22+00:00, book20_bid_proxy_usdt=831220, book20_ask_proxy_usdt=925462, funding_indicative=0.000000, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=40888288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T12:45:06+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=0.060080, depth_time=2026-10-19T12:45:29+00:00, book20_bid_proxy_usdt=242226, book20_ask_proxy_usdt=179515, funding_indicative=0.000007, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.38%, turnover=9241343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T12:45:06+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=0.059090, depth_time=2026-10-19T12:45:19+00:00, book20_bid_proxy_usdt=637315, book20_ask_proxy_usdt=583958, funding_indicative=0.000050, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=18365805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T12:45:06+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=0.614900, depth_time=2026-10-19T12:45:26+00:00, book20_bid_proxy_usdt=258154, book20_ask_proxy_usdt=282132, funding_indicative=0.000004, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=49740902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T12:45:06+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=4169.510000, depth_time=2026-10-19T12:45:34+00:00, book20_bid_proxy_usdt=214315, book20_ask_proxy_usdt=190266, funding_indicative=0.000020, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.26%, turnover=95800868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-19T12:45:05+00:00, last15m_closed_end=2026-10-19T12:45+00:00, prior8high=4183.360000, depth_time=2026-10-19T12:45:32+00:00, book20_bid_proxy_usdt=573186, book20_ask_proxy_usdt=231497, funding_indicative=0.000000, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.19%, turnover=256943401. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

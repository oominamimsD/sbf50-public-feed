# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T11:45:22Z**
- feed_generated_utc: 2026-10-19T11:45:24+00:00
- source_sha256: `76d753181c785bbc0378b52463ff4cba9c81f8cc89b0a25107c45267c47f1fab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T11:45+00:00, close=82267.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T11:00+00:00, close=82379.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.033300|-11.80|20.87|-13.19|21430534|2.46|
|STRK_USDT|0.058440|-5.06|-51.00|-6.45|18284201|3.42|
|HBAR_USDT|0.083060|-3.17|-11.43|-4.56|43924395|1.20|
|SEI_USDT|0.059440|-1.32|-16.15|-2.71|9244670|1.68|
|TIA_USDT|0.609900|-1.29|3.60|-2.68|51667716|3.28|
|SAND_USDT|0.058050|-1.20|-12.62|-2.59|15198411|1.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.033300|2.075400|2.032400|2.68|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.083060|0.082730|0.083090|1.53|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.058050|0.057570|0.058050|0.49|N|Y/Y|N/N|N|N|
|SEI_USDT|0.059440|0.059390|0.059460|2.81|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058440|0.057600|0.058440|0.75|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.609900|0.602400|0.609800|0.80|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=2.239100, depth_time=2026-10-19T11:45:08+00:00, book20_bid_proxy_usdt=7305, book20_ask_proxy_usdt=8531, funding_indicative=-0.000594, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.80%, turnover=21430534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=0.084810, depth_time=2026-10-19T11:45:13+00:00, book20_bid_proxy_usdt=398292, book20_ask_proxy_usdt=628386, funding_indicative=-0.000007, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=43924395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=0.058850, depth_time=2026-10-19T11:45:20+00:00, book20_bid_proxy_usdt=620818, book20_ask_proxy_usdt=1164433, funding_indicative=-0.002540, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=15198411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=0.060860, depth_time=2026-10-19T11:45:15+00:00, book20_bid_proxy_usdt=337467, book20_ask_proxy_usdt=366802, funding_indicative=0.000027, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=9244670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=0.060310, depth_time=2026-10-19T11:45:08+00:00, book20_bid_proxy_usdt=432572, book20_ask_proxy_usdt=666995, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.06%, turnover=18284201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T11:45:01+00:00, last15m_closed_end=2026-10-19T11:45+00:00, prior8high=0.614900, depth_time=2026-10-19T11:45:18+00:00, book20_bid_proxy_usdt=282851, book20_ask_proxy_usdt=297130, funding_indicative=0.000004, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=51667716. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

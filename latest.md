# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T11:15:21Z**
- feed_generated_utc: 2026-10-19T11:15:22+00:00
- source_sha256: `42015b22ee77cb2079b17b2315c48102a518308b29d9ddd5c6e74240d6ae9ac8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T11:15+00:00, close=82171.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T11:00+00:00, close=82379.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.120600|-8.01|26.06|-9.28|20755870|1.42|
|STRK_USDT|0.058340|-5.23|-51.08|-6.50|18003392|1.72|
|HBAR_USDT|0.082900|-3.35|-11.60|-4.62|43367102|1.21|
|TIA_USDT|0.608200|-1.56|3.31|-2.83|51042114|1.64|
|SAND_USDT|0.057900|-1.46|-12.85|-2.73|15146206|1.73|
|SEI_USDT|0.059590|-1.07|-15.94|-2.34|8996131|1.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.120600|2.104100|2.120600|1.00|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.082900|0.083140|0.082900|1.48|Y|Y/Y|Y/Y|N|Y|
|SAND_USDT|0.057900|0.057570|0.057890|0.67|N|Y/Y|N/N|N|N|
|SEI_USDT|0.059590|0.059590|0.059600|5.00|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058340|0.057600|0.058340|1.63|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.608200|0.602400|0.608200|0.68|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=2.310800, depth_time=2026-10-19T11:15:07+00:00, book20_bid_proxy_usdt=7431, book20_ask_proxy_usdt=7226, funding_indicative=-0.000564, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.01%, turnover=20755870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=0.084810, depth_time=2026-10-19T11:15:09+00:00, book20_bid_proxy_usdt=443404, book20_ask_proxy_usdt=1059985, funding_indicative=-0.000014, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=43367102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=0.059080, depth_time=2026-10-19T11:15:16+00:00, book20_bid_proxy_usdt=496163, book20_ask_proxy_usdt=865407, funding_indicative=-0.002865, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=15146206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=0.061330, depth_time=2026-10-19T11:15:20+00:00, book20_bid_proxy_usdt=240125, book20_ask_proxy_usdt=227895, funding_indicative=0.000032, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=8996131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=0.060310, depth_time=2026-10-19T11:15:09+00:00, book20_bid_proxy_usdt=775945, book20_ask_proxy_usdt=464247, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.23%, turnover=18003392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T11:15:01+00:00, last15m_closed_end=2026-10-19T11:15+00:00, prior8high=0.614100, depth_time=2026-10-19T11:15:15+00:00, book20_bid_proxy_usdt=160819, book20_ask_proxy_usdt=321393, funding_indicative=0.000003, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=51042114. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

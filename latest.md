# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T09:30:19Z**
- feed_generated_utc: 2026-10-19T09:30:20+00:00
- source_sha256: `b87405ef4e0a0d3bae584cdecbc348e593664857764dc881475ca24f05b8c2d6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T09:30+00:00, close=82948.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T09:00+00:00, close=82786, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.166100|-7.41|56.69|-9.64|6691291|6.01|
|BTW_USDT|2.210800|-4.10|31.42|-6.33|21604419|1.36|
|STRK_USDT|0.059530|-3.29|-50.08|-5.52|18087198|1.68|
|TIA_USDT|0.610700|-1.16|3.73|-3.39|56054776|1.64|
|SAND_USDT|0.058800|0.06|-11.49|-2.17|16897909|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.210800|2.179000|2.210800|1.02|N|Y/Y|N/N|N|N|
|ICNT_USDT|0.166100|0.166300|0.166100|0.91|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058800|0.058430|0.058800|0.88|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059530|0.059130|0.059530|1.77|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.610700|0.605200|0.610700|1.39|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T09:30:02+00:00, last15m_closed_end=2026-10-19T09:30+00:00, prior8high=2.310800, depth_time=2026-10-19T09:30:11+00:00, book20_bid_proxy_usdt=7212, book20_ask_proxy_usdt=12692, funding_indicative=-0.000468, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=21604419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T09:30:02+00:00, last15m_closed_end=2026-10-19T09:30+00:00, prior8high=0.175400, depth_time=2026-10-19T09:30:08+00:00, book20_bid_proxy_usdt=164476, book20_ask_proxy_usdt=172088, funding_indicative=-0.000333, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.41%, turnover=6691291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T09:30:03+00:00, last15m_closed_end=2026-10-19T09:30+00:00, prior8high=0.061170, depth_time=2026-10-19T09:30:17+00:00, book20_bid_proxy_usdt=516610, book20_ask_proxy_usdt=605947, funding_indicative=-0.004909, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.06%, turnover=16897909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T09:30:03+00:00, last15m_closed_end=2026-10-19T09:30+00:00, prior8high=0.060350, depth_time=2026-10-19T09:30:12+00:00, book20_bid_proxy_usdt=690442, book20_ask_proxy_usdt=539326, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=18087198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T09:30:02+00:00, last15m_closed_end=2026-10-19T09:30+00:00, prior8high=0.620500, depth_time=2026-10-19T09:30:15+00:00, book20_bid_proxy_usdt=201238, book20_ask_proxy_usdt=223564, funding_indicative=-0.000012, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=56054776. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T15:15:35Z**
- feed_generated_utc: 2026-10-16T15:15:37+00:00
- source_sha256: `aea7b2d8f6f1d8af5c9f477e03a8780f7b3e574bac62f18cacd99f2aa2158caf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T15:15+00:00, close=81693, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T15:00+00:00, close=81943.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.075040|-22.12|24.73|-21.30|38609473|1.33|
|PYTH_USDT|0.086650|-10.98|17.73|-10.16|8261108|1.15|
|AKE_USDT|0.028460|-9.95|-1.93|-9.13|14102580|0.35|
|PUMPFUN_USDT|0.004328|-4.37|-20.73|-3.55|16097852|2.31|
|PEPE_USDT|0.000004|-4.02|6.63|-3.20|102172382|0.25|
|UNI_USDT|7.266000|-3.69|-0.69|-2.87|15645044|1.38|
|FET_USDT|0.201700|-3.49|-6.05|-2.67|10975418|4.96|
|JUP_USDT|0.303200|-3.06|-12.74|-2.24|5682820|3.30|
|QNT_USDT|202.940000|-2.39|-11.40|-1.57|68357493|0.49|
|HYPE_USDT|79.754000|-2.33|-4.31|-1.51|68512904|0.12|
|ADA_USDT|0.225500|-2.16|-2.54|-1.34|42057253|4.44|
|XLM_USDT|0.181330|-2.01|-4.11|-1.19|10901822|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.225500|0.227400|0.225500|6.24|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.028460|0.028561|0.028460|2.18|Y|Y/Y|N/N|Y|N|
|FET_USDT|0.201700|0.203000|0.202000|3.47|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|79.754000|80.146000|79.814000|2.81|Y|Y/Y|N/Y|Y|N|
|JUP_USDT|0.303200|0.306100|0.303200|5.13|Y|Y/Y|Y/Y|Y|Y|
|PEPE_USDT|0.000004|0.000004|0.000004|2.47|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004328|0.004373|0.004330|8.11|Y|Y/Y|Y/Y|Y|Y|
|PYTH_USDT|0.086650|0.087240|0.086650|2.73|Y|Y/Y|N/N|Y|N|
|QNT_USDT|202.940000|205.250000|202.940000|2.55|Y|Y/Y|N/Y|Y|N|
|STRK_USDT|0.075040|0.075560|0.075040|2.20|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|7.266000|7.361000|7.266000|6.05|Y|Y/Y|N/N|Y|N|
|XLM_USDT|0.181330|0.182000|0.181330|3.84|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.230800, depth_time=2026-10-16T15:15:31+00:00, book20_bid_proxy_usdt=6138715, book20_ask_proxy_usdt=4977370, funding_indicative=-0.000022, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=42057253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.029713, depth_time=2026-10-16T15:15:12+00:00, book20_bid_proxy_usdt=16487, book20_ask_proxy_usdt=14420, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.95%, turnover=14102580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.206900, depth_time=2026-10-16T15:15:22+00:00, book20_bid_proxy_usdt=1744858, book20_ask_proxy_usdt=1158058, funding_indicative=0.000100, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=10975418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=81.537000, depth_time=2026-10-16T15:15:29+00:00, book20_bid_proxy_usdt=205886, book20_ask_proxy_usdt=250332, funding_indicative=-0.000005, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=68512904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.310600, depth_time=2026-10-16T15:15:22+00:00, book20_bid_proxy_usdt=387650, book20_ask_proxy_usdt=334394, funding_indicative=-0.000031, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=5682820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.000004, depth_time=2026-10-16T15:15:17+00:00, book20_bid_proxy_usdt=66152, book20_ask_proxy_usdt=38303, funding_indicative=0.000054, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=102172382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.004461, depth_time=2026-10-16T15:15:15+00:00, book20_bid_proxy_usdt=1516107, book20_ask_proxy_usdt=977071, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=16097852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.089670, depth_time=2026-10-16T15:15:10+00:00, book20_bid_proxy_usdt=59617, book20_ask_proxy_usdt=85890, funding_indicative=0.000008, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.98%, turnover=8261108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=208.400000, depth_time=2026-10-16T15:15:27+00:00, book20_bid_proxy_usdt=33407, book20_ask_proxy_usdt=67178, funding_indicative=0.000001, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=68357493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.077680, depth_time=2026-10-16T15:15:08+00:00, book20_bid_proxy_usdt=309813, book20_ask_proxy_usdt=252922, funding_indicative=-0.000028, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.12%, turnover=38609473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=7.456000, depth_time=2026-10-16T15:15:20+00:00, book20_bid_proxy_usdt=874887, book20_ask_proxy_usdt=2094510, funding_indicative=-0.000009, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=15645044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-16T15:15:02+00:00, last15m_closed_end=2026-10-16T15:15+00:00, prior8high=0.184250, depth_time=2026-10-16T15:15:34+00:00, book20_bid_proxy_usdt=182999, book20_ask_proxy_usdt=154281, funding_indicative=-0.000083, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=10901822. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

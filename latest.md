# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T01:45:29Z**
- feed_generated_utc: 2026-10-31T01:45:31+00:00
- source_sha256: `5577a02f09bba2b050536608a928f7c0afad091ee49fd334ea996e9c6d984933`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T01:45+00:00, close=77425.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T01:00+00:00, close=77521.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012906|-31.79|-63.12|-31.60|6157791|4.65|
|Q_USDT|0.037080|-21.90|-68.66|-21.71|19209079|5.39|
|EVAA_USDT|1.136900|-11.32|116.59|-11.13|6609022|6.16|
|BEAT_USDT|0.098020|-6.78|35.03|-6.59|8517514|4.09|
|BLESS_USDT|0.009328|-5.30|14.29|-5.11|12538015|3.22|
|BTW_USDT|1.139300|-5.01|-33.07|-4.82|9640627|2.63|
|TRX_USDT|0.322860|-3.76|-1.96|-3.57|8742586|0.31|
|HYPE_USDT|89.299000|-3.29|13.89|-3.10|129538869|0.11|
|LIT_USDT|2.769800|-1.92|-16.67|-1.73|6809017|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012906|0.012618|0.012906|0.50|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098020|0.098180|0.098090|2.28|Y|N/N|N/N|Y|N|
|BLESS_USDT|0.009328|0.009305|0.009328|1.68|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.139300|1.107500|1.138100|0.52|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.136900|1.106900|1.136400|0.94|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.299000|89.156000|89.299000|0.31|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.769800|2.749900|2.769800|0.75|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.037080|0.035810|0.037070|2.41|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.322860|0.321930|0.323060|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=0.014253, depth_time=2026-10-31T01:45:08+00:00, book20_bid_proxy_usdt=6562, book20_ask_proxy_usdt=4485, funding_indicative=-0.000017, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-31.79%, turnover=6157791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=0.106950, depth_time=2026-10-31T01:45:16+00:00, book20_bid_proxy_usdt=11678, book20_ask_proxy_usdt=4954, funding_indicative=0.000187, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.78%, turnover=8517514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=0.009963, depth_time=2026-10-31T01:45:18+00:00, book20_bid_proxy_usdt=11404, book20_ask_proxy_usdt=21086, funding_indicative=0.000080, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.30%, turnover=12538015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=1.161000, depth_time=2026-10-31T01:45:20+00:00, book20_bid_proxy_usdt=17547, book20_ask_proxy_usdt=11758, funding_indicative=-0.000367, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.01%, turnover=9640627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=1.176200, depth_time=2026-10-31T01:45:13+00:00, book20_bid_proxy_usdt=7292, book20_ask_proxy_usdt=7198, funding_indicative=0.000073, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.32%, turnover=6609022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=90.278000, depth_time=2026-10-31T01:45:26+00:00, book20_bid_proxy_usdt=150396, book20_ask_proxy_usdt=47499, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=129538869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=2.789800, depth_time=2026-10-31T01:45:28+00:00, book20_bid_proxy_usdt=54795, book20_ask_proxy_usdt=27137, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=6809017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=0.049970, depth_time=2026-10-31T01:45:11+00:00, book20_bid_proxy_usdt=23226, book20_ask_proxy_usdt=29497, funding_indicative=-0.000022, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.90%, turnover=19209079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T01:45:01+00:00, last15m_closed_end=2026-10-31T01:45+00:00, prior8high=0.330860, depth_time=2026-10-31T01:45:23+00:00, book20_bid_proxy_usdt=63927, book20_ask_proxy_usdt=54466, funding_indicative=-0.001248, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=8742586. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

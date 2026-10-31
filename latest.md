# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T15:15:36Z**
- feed_generated_utc: 2026-10-31T15:15:38+00:00
- source_sha256: `1d9dfe835accba0f58397daaed4cd6ba10c8d3030e627f127a1afbaf962974d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T15:15+00:00, close=77416.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T15:00+00:00, close=77382.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011160|-41.01|-68.11|-40.80|12189418|2.69|
|Q_USDT|0.032420|-31.71|-72.60|-31.50|11469494|3.08|
|BEAT_USDT|0.098440|-6.38|35.61|-6.17|6526406|1.02|
|TRX_USDT|0.314430|-6.28|-4.52|-6.07|6483780|0.32|
|HYPE_USDT|87.070000|-5.71|11.05|-5.50|92596490|0.12|
|BTW_USDT|1.142300|-4.76|-32.90|-4.55|7968641|1.75|
|WLD_USDT|0.400800|-2.69|-24.71|-2.48|40482714|2.49|
|FET_USDT|0.162300|-2.58|-13.34|-2.37|5539540|6.16|
|IDOL_USDT|0.019724|-2.55|149.04|-2.34|15562899|4.04|
|BCH_USDT|288.180000|-1.75|0.25|-1.54|5239419|7.98|
|DASH_USDT|48.390000|-1.32|-10.13|-1.11|6765311|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011160|0.010919|0.011214|1.62|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|288.180000|288.650000|288.180000|0.98|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.098440|0.096930|0.098440|1.11|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.142300|1.095000|1.142000|0.67|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.390000|47.750000|48.390000|3.00|N|N/Y|Y/Y|Y|N|
|FET_USDT|0.162300|0.160500|0.162300|4.25|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.070000|86.372000|87.054000|0.32|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019724|0.018799|0.019724|0.80|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032420|0.031650|0.032420|1.83|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.314430|0.315230|0.314420|1.54|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.400800|0.395200|0.400700|3.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.011940, depth_time=2026-10-31T15:15:09+00:00, book20_bid_proxy_usdt=11842, book20_ask_proxy_usdt=12994, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-41.01%, turnover=12189418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=292.880000, depth_time=2026-10-31T15:15:32+00:00, book20_bid_proxy_usdt=44786, book20_ask_proxy_usdt=381077, funding_indicative=0.000059, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=5239419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.100370, depth_time=2026-10-31T15:15:13+00:00, book20_bid_proxy_usdt=10694, book20_ask_proxy_usdt=12896, funding_indicative=0.000129, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.38%, turnover=6526406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=1.149700, depth_time=2026-10-31T15:15:22+00:00, book20_bid_proxy_usdt=14723, book20_ask_proxy_usdt=20921, funding_indicative=-0.000094, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=7968641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=48.500000, depth_time=2026-10-31T15:15:33+00:00, book20_bid_proxy_usdt=713929, book20_ask_proxy_usdt=731999, funding_indicative=-0.000116, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=6765311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.162200, depth_time=2026-10-31T15:15:26+00:00, book20_bid_proxy_usdt=1587508, book20_ask_proxy_usdt=1050957, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=5539540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=88.467000, depth_time=2026-10-31T15:15:19+00:00, book20_bid_proxy_usdt=34868, book20_ask_proxy_usdt=346217, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=92596490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.020565, depth_time=2026-10-31T15:15:27+00:00, book20_bid_proxy_usdt=5824, book20_ask_proxy_usdt=4819, funding_indicative=0.000230, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=15562899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.033470, depth_time=2026-10-31T15:15:11+00:00, book20_bid_proxy_usdt=63276, book20_ask_proxy_usdt=43009, funding_indicative=-0.000533, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=1, 24h_change=-31.71%, turnover=11469494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.319700, depth_time=2026-10-31T15:15:16+00:00, book20_bid_proxy_usdt=75488, book20_ask_proxy_usdt=96950, funding_indicative=-0.000601, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.28%, turnover=6483780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T15:15:02+00:00, last15m_closed_end=2026-10-31T15:15+00:00, prior8high=0.399000, depth_time=2026-10-31T15:15:23+00:00, book20_bid_proxy_usdt=3255507, book20_ask_proxy_usdt=2981032, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=40482714. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

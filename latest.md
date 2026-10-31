# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T15:45:31Z**
- feed_generated_utc: 2026-10-31T15:45:34+00:00
- source_sha256: `2821956371af7ef715dc5a80e92531838c028ef90cf1d74fe92011f6360def6e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T15:45+00:00, close=77553.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T15:00+00:00, close=77382.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011225|-40.67|-67.92|-40.64|12309655|3.57|
|Q_USDT|0.031930|-32.75|-73.01|-32.72|11573883|6.27|
|IDOL_USDT|0.018243|-9.87|130.34|-9.84|15812044|3.83|
|TRX_USDT|0.312510|-6.85|-5.11|-6.82|6732506|0.32|
|BTW_USDT|1.122400|-6.42|-34.06|-6.39|8061763|2.67|
|BEAT_USDT|0.099170|-5.68|36.61|-5.65|6629028|2.02|
|HYPE_USDT|87.926000|-4.78|12.14|-4.75|94694267|0.11|
|FET_USDT|0.163600|-1.80|-12.65|-1.77|5843430|6.12|
|PEPE_USDT|0.000005|-1.55|2.48|-1.52|97365051|0.20|
|BCH_USDT|288.750000|-1.55|0.44|-1.52|5270543|6.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011225|0.010824|0.011212|0.44|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|288.750000|287.880000|288.750000|0.20|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.099170|0.096930|0.099170|1.30|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.122400|1.095000|1.122000|1.00|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163600|0.160600|0.163600|1.91|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.926000|86.372000|87.953000|1.25|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018243|0.019100|0.018288|7.04|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.76|N|N/Y|N/N|Y|N|
|Q_USDT|0.031930|0.031950|0.031910|1.22|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.312510|0.313160|0.312510|1.32|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T15:45:03+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.011929, depth_time=2026-10-31T15:45:09+00:00, book20_bid_proxy_usdt=10132, book20_ask_proxy_usdt=6377, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-40.67%, turnover=12309655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-31T15:45:04+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=291.130000, depth_time=2026-10-31T15:45:30+00:00, book20_bid_proxy_usdt=27308, book20_ask_proxy_usdt=68680, funding_indicative=0.000048, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=5270543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T15:45:04+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.100370, depth_time=2026-10-31T15:45:20+00:00, book20_bid_proxy_usdt=11242, book20_ask_proxy_usdt=14220, funding_indicative=0.000140, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=6629028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T15:45:04+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=1.152900, depth_time=2026-10-31T15:45:18+00:00, book20_bid_proxy_usdt=9982, book20_ask_proxy_usdt=11910, funding_indicative=-0.000076, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.42%, turnover=8061763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T15:45:04+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.163000, depth_time=2026-10-31T15:45:25+00:00, book20_bid_proxy_usdt=1594080, book20_ask_proxy_usdt=784427, funding_indicative=0.000073, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=5843430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T15:45:03+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=87.815000, depth_time=2026-10-31T15:45:23+00:00, book20_bid_proxy_usdt=60822, book20_ask_proxy_usdt=260223, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=94694267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T15:45:03+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.020565, depth_time=2026-10-31T15:45:14+00:00, book20_bid_proxy_usdt=8449, book20_ask_proxy_usdt=27674, funding_indicative=0.000135, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.87%, turnover=15812044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T15:45:03+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.000005, depth_time=2026-10-31T15:45:28+00:00, book20_bid_proxy_usdt=38257, book20_ask_proxy_usdt=33839, funding_indicative=-0.000726, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=97365051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T15:45:03+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.033470, depth_time=2026-10-31T15:45:11+00:00, book20_bid_proxy_usdt=43240, book20_ask_proxy_usdt=46832, funding_indicative=-0.000613, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=1, 24h_change=-32.75%, turnover=11573883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T15:45:04+00:00, last15m_closed_end=2026-10-31T15:45+00:00, prior8high=0.319060, depth_time=2026-10-31T15:45:16+00:00, book20_bid_proxy_usdt=79107, book20_ask_proxy_usdt=65923, funding_indicative=-0.000561, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.85%, turnover=6732506. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T06:30:35Z**
- feed_generated_utc: 2026-10-31T06:30:37+00:00
- source_sha256: `607d9b44a599e8c78f1aee64eb6f7dc8e30336cb01afc9889f0619ce31cf4540`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T06:30+00:00, close=77248.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T06:00+00:00, close=77232.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011579|-38.80|-66.91|-38.38|6826540|5.19|
|Q_USDT|0.032000|-32.60|-72.95|-32.18|19643642|3.11|
|EVAA_USDT|1.171000|-8.66|123.09|-8.24|6127451|5.97|
|BEAT_USDT|0.097110|-7.64|33.77|-7.22|8566619|1.03|
|BTW_USDT|1.129700|-5.81|-33.64|-5.39|9555974|1.77|
|HYPE_USDT|88.238000|-4.44|12.54|-4.02|108189272|0.11|
|WLD_USDT|0.399600|-2.98|-24.94|-2.56|48662364|2.50|
|TRX_USDT|0.325500|-2.98|-1.16|-2.56|6735314|0.31|
|DASH_USDT|48.020000|-2.07|-10.82|-1.65|14836605|2.08|
|FET_USDT|0.163300|-1.98|-12.81|-1.56|6523018|6.13|
|PEPE_USDT|0.000005|-1.56|2.47|-1.14|132128167|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011579|0.010838|0.011579|0.91|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097110|0.096280|0.097110|0.91|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.129700|1.108600|1.129700|0.96|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.020000|47.920000|48.020000|0.19|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.171000|1.141300|1.171000|1.57|N|N/N|N/N|Y|N|
|FET_USDT|0.163300|0.162200|0.163300|1.58|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.238000|88.125000|88.238000|2.38|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.17|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032000|0.027250|0.032000|0.49|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325500|0.322650|0.325500|1.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399600|0.392600|0.399600|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.011974, depth_time=2026-10-31T06:30:09+00:00, book20_bid_proxy_usdt=5533, book20_ask_proxy_usdt=5824, funding_indicative=-0.000130, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-38.80%, turnover=6826540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.100160, depth_time=2026-10-31T06:30:16+00:00, book20_bid_proxy_usdt=21157, book20_ask_proxy_usdt=10166, funding_indicative=0.000125, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.64%, turnover=8566619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=1.176300, depth_time=2026-10-31T06:30:19+00:00, book20_bid_proxy_usdt=11611, book20_ask_proxy_usdt=12873, funding_indicative=-0.000417, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.81%, turnover=9555974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T06:30:03+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=48.350000, depth_time=2026-10-31T06:30:27+00:00, book20_bid_proxy_usdt=903123, book20_ask_proxy_usdt=772181, funding_indicative=0.000068, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=14836605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=1.242000, depth_time=2026-10-31T06:30:14+00:00, book20_bid_proxy_usdt=5590, book20_ask_proxy_usdt=6967, funding_indicative=0.000187, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.66%, turnover=6127451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T06:30:03+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.164200, depth_time=2026-10-31T06:30:32+00:00, book20_bid_proxy_usdt=1211930, book20_ask_proxy_usdt=800278, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=6523018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=89.478000, depth_time=2026-10-31T06:30:21+00:00, book20_bid_proxy_usdt=111685, book20_ask_proxy_usdt=95989, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=108189272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.000005, depth_time=2026-10-31T06:30:34+00:00, book20_bid_proxy_usdt=28836, book20_ask_proxy_usdt=39629, funding_indicative=-0.000021, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=132128167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.031680, depth_time=2026-10-31T06:30:12+00:00, book20_bid_proxy_usdt=63238, book20_ask_proxy_usdt=49300, funding_indicative=-0.000770, next_funding_utc=2026-10-31T07:00:00+00:00, funding_cycle_h=1, 24h_change=-32.60%, turnover=19643642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.327290, depth_time=2026-10-31T06:30:26+00:00, book20_bid_proxy_usdt=49168, book20_ask_proxy_usdt=45148, funding_indicative=-0.000833, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=6735314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T06:30:02+00:00, last15m_closed_end=2026-10-31T06:30+00:00, prior8high=0.400600, depth_time=2026-10-31T06:30:24+00:00, book20_bid_proxy_usdt=2789827, book20_ask_proxy_usdt=3076469, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=48662364. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

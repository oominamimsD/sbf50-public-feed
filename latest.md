# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T07:00:30Z**
- feed_generated_utc: 2026-10-31T07:00:32+00:00
- source_sha256: `367e467e7a318ec2e0841cd87e7b0162c950a42ae6f5ffa3a27b00ebf2f6f30f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T07:00+00:00, close=77350.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T07:00+00:00, close=77350.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.012308|-35.98|-64.83|-35.72|6952322|3.24|
|Q_USDT|0.032060|-32.47|-72.90|-32.21|18819686|3.12|
|EVAA_USDT|1.190600|-7.69|126.82|-7.43|5765126|5.04|
|BEAT_USDT|0.098200|-6.60|35.28|-6.34|8341850|1.02|
|BTW_USDT|1.138900|-6.44|-33.10|-6.18|9415310|1.75|
|HYPE_USDT|88.712000|-3.93|13.14|-3.67|105617231|0.11|
|TRX_USDT|0.324080|-3.40|-1.59|-3.14|5971869|0.31|
|WLD_USDT|0.399100|-3.10|-25.03|-2.84|47757613|2.50|
|DASH_USDT|48.000000|-2.37|-10.86|-2.11|14040988|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.012308|0.010838|0.012314|0.83|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.098200|0.096280|0.098060|1.04|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.138900|1.108600|1.138900|0.61|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.000000|47.870000|48.000000|0.40|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.190600|1.141300|1.190600|0.58|N|Y/Y|N/N|Y|N|
|HYPE_USDT|88.712000|88.038000|88.715000|2.31|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032060|0.027380|0.032120|0.46|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.324080|0.323840|0.324120|0.19|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.399100|0.392800|0.399200|0.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=0.012458, depth_time=2026-10-31T07:00:09+00:00, book20_bid_proxy_usdt=7322, book20_ask_proxy_usdt=11605, funding_indicative=-0.000138, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-35.98%, turnover=6952322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=0.098920, depth_time=2026-10-31T07:00:16+00:00, book20_bid_proxy_usdt=9979, book20_ask_proxy_usdt=24439, funding_indicative=0.000171, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.60%, turnover=8341850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=1.176300, depth_time=2026-10-31T07:00:19+00:00, book20_bid_proxy_usdt=15542, book20_ask_proxy_usdt=8526, funding_indicative=-0.000608, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.44%, turnover=9415310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=48.190000, depth_time=2026-10-31T07:00:29+00:00, book20_bid_proxy_usdt=536455, book20_ask_proxy_usdt=660640, funding_indicative=0.000093, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=14040988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=1.242000, depth_time=2026-10-31T07:00:14+00:00, book20_bid_proxy_usdt=11297, book20_ask_proxy_usdt=4652, funding_indicative=0.000224, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.69%, turnover=5765126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=89.040000, depth_time=2026-10-31T07:00:22+00:00, book20_bid_proxy_usdt=138447, book20_ask_proxy_usdt=136402, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=105617231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=0.032790, depth_time=2026-10-31T07:00:11+00:00, book20_bid_proxy_usdt=52306, book20_ask_proxy_usdt=48870, funding_indicative=-0.000786, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=1, 24h_change=-32.47%, turnover=18819686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=0.326690, depth_time=2026-10-31T07:00:24+00:00, book20_bid_proxy_usdt=107154, book20_ask_proxy_usdt=62771, funding_indicative=-0.000680, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.40%, turnover=5971869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T07:00:03+00:00, last15m_closed_end=2026-10-31T07:00+00:00, prior8high=0.400300, depth_time=2026-10-31T07:00:27+00:00, book20_bid_proxy_usdt=3431464, book20_ask_proxy_usdt=2627686, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=47757613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

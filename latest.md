# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T11:15:36Z**
- feed_generated_utc: 2026-10-31T11:15:38+00:00
- source_sha256: `6e29297bd34f2a6d70a8f7a1d3bcc476e5e73c7fa7cc173bed78b5e5acf1c3fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T11:15+00:00, close=77387.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T11:00+00:00, close=77376.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011267|-40.45|-67.80|-40.21|10503980|2.67|
|Q_USDT|0.031960|-32.68|-72.99|-32.44|13058506|3.12|
|IDOL_USDT|0.018963|-6.31|139.43|-6.07|16010079|2.64|
|BTW_USDT|1.138400|-5.09|-33.12|-4.85|8864469|3.52|
|HYPE_USDT|87.728000|-4.99|11.89|-4.75|96814624|0.11|
|TRX_USDT|0.319850|-4.66|-2.88|-4.42|7027316|1.25|
|WLD_USDT|0.396000|-3.86|-25.61|-3.62|45721087|2.53|
|FET_USDT|0.161100|-3.30|-13.98|-3.06|5857476|6.21|
|DASH_USDT|47.750000|-2.63|-11.32|-2.39|11592897|2.09|
|LTC_USDT|54.900000|-1.47|-6.07|-1.23|6092064|3.64|
|PEPE_USDT|0.000005|-1.43|2.60|-1.19|120949740|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011267|0.010360|0.011266|1.67|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.138400|1.118100|1.138400|0.51|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.750000|47.730000|47.760000|2.27|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161100|0.161100|0.161100|2.66|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.728000|86.889000|87.728000|0.28|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018963|0.017952|0.018942|0.56|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.900000|54.650000|54.900000|0.14|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.30|N|N/N|N/N|Y|N|
|Q_USDT|0.031960|0.031080|0.031960|0.86|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.319850|0.315970|0.319850|1.25|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396000|0.395100|0.396000|2.59|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.011111, depth_time=2026-10-31T11:15:10+00:00, book20_bid_proxy_usdt=8024, book20_ask_proxy_usdt=11793, funding_indicative=-0.000127, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.45%, turnover=10503980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=1.150100, depth_time=2026-10-31T11:15:17+00:00, book20_bid_proxy_usdt=53127, book20_ask_proxy_usdt=13563, funding_indicative=-0.000225, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=8864469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T11:15:01+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=48.060000, depth_time=2026-10-31T11:15:28+00:00, book20_bid_proxy_usdt=809744, book20_ask_proxy_usdt=631580, funding_indicative=-0.000164, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=11592897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T11:15:01+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.162400, depth_time=2026-10-31T11:15:27+00:00, book20_bid_proxy_usdt=1386686, book20_ask_proxy_usdt=940900, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=5857476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=88.220000, depth_time=2026-10-31T11:15:19+00:00, book20_bid_proxy_usdt=88837, book20_ask_proxy_usdt=154532, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=96814624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.019981, depth_time=2026-10-31T11:15:14+00:00, book20_bid_proxy_usdt=3206, book20_ask_proxy_usdt=11845, funding_indicative=0.000220, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.31%, turnover=16010079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T11:15:01+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=55.000000, depth_time=2026-10-31T11:15:32+00:00, book20_bid_proxy_usdt=1383481, book20_ask_proxy_usdt=1373816, funding_indicative=-0.000052, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=6092064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.000005, depth_time=2026-10-31T11:15:34+00:00, book20_bid_proxy_usdt=22928, book20_ask_proxy_usdt=34282, funding_indicative=-0.000720, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=120949740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.033810, depth_time=2026-10-31T11:15:12+00:00, book20_bid_proxy_usdt=58423, book20_ask_proxy_usdt=67357, funding_indicative=-0.000551, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=1, 24h_change=-32.68%, turnover=13058506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.319730, depth_time=2026-10-31T11:15:22+00:00, book20_bid_proxy_usdt=50870, book20_ask_proxy_usdt=45600, funding_indicative=-0.001158, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.66%, turnover=7027316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T11:15:00+00:00, last15m_closed_end=2026-10-31T11:15+00:00, prior8high=0.399000, depth_time=2026-10-31T11:15:24+00:00, book20_bid_proxy_usdt=3306067, book20_ask_proxy_usdt=4055527, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=45721087. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

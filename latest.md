# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T09:30:44Z**
- feed_generated_utc: 2026-10-31T09:30:47+00:00
- source_sha256: `27661c2bc25c0d6929efaed8abc1c077aa02b421726b64dd71cd7501953c1394`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T09:30+00:00, close=77418.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T09:00+00:00, close=77320.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010582|-44.07|-69.76|-43.87|10051581|5.67|
|Q_USDT|0.033470|-29.50|-71.71|-29.30|15375871|2.99|
|IDOL_USDT|0.018732|-7.45|136.51|-7.25|15731308|6.42|
|HYPE_USDT|87.483000|-5.26|11.57|-5.06|103704690|0.11|
|BTW_USDT|1.137500|-5.16|-33.18|-4.96|9184813|0.88|
|BEAT_USDT|0.099720|-5.16|37.37|-4.96|8237211|4.01|
|TRX_USDT|0.318370|-5.10|-3.33|-4.90|6448498|0.31|
|WLD_USDT|0.397500|-3.49|-25.33|-3.29|48612916|2.52|
|EVAA_USDT|1.241900|-3.13|136.59|-2.93|5393990|3.22|
|FET_USDT|0.162000|-2.76|-13.50|-2.56|5893226|6.17|
|DASH_USDT|47.850000|-2.42|-11.14|-2.22|13339525|2.09|
|LTC_USDT|54.820000|-1.61|-6.21|-1.41|6429555|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010582|0.009146|0.010582|1.03|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099720|0.096500|0.099720|1.55|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.137500|1.126300|1.137500|0.83|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.850000|47.590000|47.860000|0.42|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.241900|1.191200|1.241900|2.23|N|N/N|N/N|Y|N|
|FET_USDT|0.162000|0.161500|0.162000|1.34|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.483000|86.343000|87.483000|0.75|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018732|0.018443|0.018734|2.15|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.820000|54.520000|54.820000|1.19|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.033470|0.031580|0.033470|0.70|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318370|0.318590|0.318370|1.76|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.397500|0.394600|0.397500|1.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.013245, depth_time=2026-10-31T09:30:08+00:00, book20_bid_proxy_usdt=7215, book20_ask_proxy_usdt=11801, funding_indicative=-0.001030, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.07%, turnover=10051581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.100780, depth_time=2026-10-31T09:30:21+00:00, book20_bid_proxy_usdt=11429, book20_ask_proxy_usdt=7014, funding_indicative=0.000168, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=8237211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=1.181700, depth_time=2026-10-31T09:30:19+00:00, book20_bid_proxy_usdt=11724, book20_ask_proxy_usdt=14024, funding_indicative=-0.000181, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=9184813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=48.110000, depth_time=2026-10-31T09:30:31+00:00, book20_bid_proxy_usdt=835263, book20_ask_proxy_usdt=622774, funding_indicative=-0.000016, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=13339525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=1.236300, depth_time=2026-10-31T09:30:28+00:00, book20_bid_proxy_usdt=4831, book20_ask_proxy_usdt=4210, funding_indicative=0.000288, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=5393990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.163400, depth_time=2026-10-31T09:30:31+00:00, book20_bid_proxy_usdt=1431149, book20_ask_proxy_usdt=940208, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=5893226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=88.695000, depth_time=2026-10-31T09:30:16+00:00, book20_bid_proxy_usdt=188090, book20_ask_proxy_usdt=112033, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.26%, turnover=103704690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.023499, depth_time=2026-10-31T09:30:14+00:00, book20_bid_proxy_usdt=6089, book20_ask_proxy_usdt=5588, funding_indicative=0.000215, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.45%, turnover=15731308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=55.160000, depth_time=2026-10-31T09:30:36+00:00, book20_bid_proxy_usdt=1018656, book20_ask_proxy_usdt=1405722, funding_indicative=0.000008, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=6429555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.033790, depth_time=2026-10-31T09:30:11+00:00, book20_bid_proxy_usdt=37674, book20_ask_proxy_usdt=105165, funding_indicative=-0.000629, next_funding_utc=2026-10-31T10:00:00+00:00, funding_cycle_h=1, 24h_change=-29.50%, turnover=15375871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.324250, depth_time=2026-10-31T09:30:24+00:00, book20_bid_proxy_usdt=12847302, book20_ask_proxy_usdt=93597, funding_indicative=-0.000535, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=6448498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T09:30:02+00:00, last15m_closed_end=2026-10-31T09:30+00:00, prior8high=0.400400, depth_time=2026-10-31T09:30:23+00:00, book20_bid_proxy_usdt=3322083, book20_ask_proxy_usdt=2981684, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=48612916. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

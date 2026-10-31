# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T05:00:34Z**
- feed_generated_utc: 2026-10-31T05:00:36+00:00
- source_sha256: `841babef5eff55930f028fd74f6620ea32fa7312eaa8f9dd4abb447a2c652ad3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T05:00+00:00, close=77154.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T05:00+00:00, close=77154.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011093|-41.37|-68.30|-40.83|6522827|2.70|
|EVAA_USDT|1.172900|-9.07|123.45|-8.53|6273248|3.41|
|BEAT_USDT|0.097880|-7.42|34.83|-6.88|8538920|1.02|
|BTW_USDT|1.132900|-6.93|-33.45|-6.39|9377947|1.76|
|PEPE_USDT|0.000005|-6.13|-0.69|-5.59|134051287|0.21|
|LIT_USDT|2.730800|-4.65|-17.84|-4.11|5076333|0.37|
|HYPE_USDT|88.592000|-4.47|12.99|-3.93|109461750|0.11|
|TRX_USDT|0.325470|-3.25|-1.17|-2.71|6766400|0.61|
|DASH_USDT|48.050000|-2.27|-10.77|-1.73|15726637|2.08|
|WLD_USDT|0.394600|-2.20|-25.88|-1.66|49593499|2.53|
|ARB_USDT|0.160550|-1.84|-10.77|-1.30|21404591|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011093|0.011238|0.011073|1.29|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160550|0.159750|0.160550|1.42|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097880|0.097280|0.097880|1.29|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.132900|1.119500|1.132900|0.79|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.050000|47.930000|48.050000|1.40|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.172900|1.166900|1.172900|1.04|N|Y/N|N/N|Y|N|
|HYPE_USDT|88.592000|88.396000|88.592000|3.97|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.730800|2.720200|2.730800|1.21|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.11|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.325470|0.322650|0.325410|0.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.394600|0.392600|0.394600|1.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.012057, depth_time=2026-10-31T05:00:08+00:00, book20_bid_proxy_usdt=19240, book20_ask_proxy_usdt=9713, funding_indicative=-0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-41.37%, turnover=6522827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.162460, depth_time=2026-10-31T05:00:33+00:00, book20_bid_proxy_usdt=63614, book20_ask_proxy_usdt=53448, funding_indicative=0.000009, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=21404591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.101470, depth_time=2026-10-31T05:00:13+00:00, book20_bid_proxy_usdt=13199, book20_ask_proxy_usdt=9551, funding_indicative=0.000122, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.42%, turnover=8538920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=1.224900, depth_time=2026-10-31T05:00:16+00:00, book20_bid_proxy_usdt=10798, book20_ask_proxy_usdt=10474, funding_indicative=-0.000427, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.93%, turnover=9377947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=48.750000, depth_time=2026-10-31T05:00:27+00:00, book20_bid_proxy_usdt=642786, book20_ask_proxy_usdt=676816, funding_indicative=0.000059, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=15726637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=1.292600, depth_time=2026-10-31T05:00:11+00:00, book20_bid_proxy_usdt=12972, book20_ask_proxy_usdt=12348, funding_indicative=0.000180, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.07%, turnover=6273248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=90.126000, depth_time=2026-10-31T05:00:23+00:00, book20_bid_proxy_usdt=205612, book20_ask_proxy_usdt=136586, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.47%, turnover=109461750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=2.790900, depth_time=2026-10-31T05:00:20+00:00, book20_bid_proxy_usdt=23239, book20_ask_proxy_usdt=21992, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=5076333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.000005, depth_time=2026-10-31T05:00:18+00:00, book20_bid_proxy_usdt=20016, book20_ask_proxy_usdt=37591, funding_indicative=-0.000199, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.13%, turnover=134051287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.327950, depth_time=2026-10-31T05:00:24+00:00, book20_bid_proxy_usdt=40698, book20_ask_proxy_usdt=32756, funding_indicative=-0.001332, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=6766400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T05:00:03+00:00, last15m_closed_end=2026-10-31T05:00+00:00, prior8high=0.402800, depth_time=2026-10-31T05:00:30+00:00, book20_bid_proxy_usdt=3346204, book20_ask_proxy_usdt=3619401, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=49593499. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

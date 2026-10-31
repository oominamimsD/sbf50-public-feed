# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T13:45:37Z**
- feed_generated_utc: 2026-10-31T13:45:39+00:00
- source_sha256: `0ffe50a7e6c8121312cf3be88d44efa6000868611056a801505f40f1a0997df5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T13:45+00:00, close=77510.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T13:00+00:00, close=77509.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011577|-38.81|-66.92|-38.73|11610569|2.59|
|Q_USDT|0.032210|-32.16|-72.78|-32.08|12243972|3.10|
|BTW_USDT|1.098900|-8.38|-35.44|-8.30|8544891|4.55|
|HYPE_USDT|87.518000|-5.22|11.62|-5.14|97026116|0.11|
|TRX_USDT|0.318500|-5.06|-3.29|-4.98|6689424|0.31|
|BEAT_USDT|0.100280|-4.63|38.14|-4.55|7394002|3.00|
|WLD_USDT|0.397900|-3.39|-25.26|-3.31|43154786|2.51|
|FET_USDT|0.161000|-3.36|-14.04|-3.28|6266442|6.21|
|IDOL_USDT|0.019744|-2.46|149.29|-2.38|16070737|1.01|
|DASH_USDT|48.040000|-2.03|-10.78|-1.95|9625235|2.08|
|PEPE_USDT|0.000005|-1.36|2.68|-1.28|110281314|0.20|
|LTC_USDT|55.040000|-1.22|-5.83|-1.14|5813702|3.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011577|0.011231|0.011551|0.90|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100280|0.098720|0.100280|1.35|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.098900|1.081300|1.098900|1.67|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.040000|47.750000|48.050000|1.28|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161000|0.160400|0.161000|3.78|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.518000|87.035000|87.518000|0.96|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019744|0.018799|0.019744|0.84|N|Y/Y|N/N|Y|N|
|LTC_USDT|55.040000|54.780000|55.040000|0.69|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.69|N|N/N|N/N|Y|N|
|Q_USDT|0.032210|0.031390|0.032210|1.03|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318500|0.317290|0.318410|0.08|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397900|0.394200|0.397900|1.55|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.012080, depth_time=2026-10-31T13:45:08+00:00, book20_bid_proxy_usdt=12261, book20_ask_proxy_usdt=3168, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-38.81%, turnover=11610569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.101620, depth_time=2026-10-31T13:45:21+00:00, book20_bid_proxy_usdt=12814, book20_ask_proxy_usdt=5331, funding_indicative=0.000172, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.63%, turnover=7394002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=1.204600, depth_time=2026-10-31T13:45:13+00:00, book20_bid_proxy_usdt=14172, book20_ask_proxy_usdt=11005, funding_indicative=-0.000370, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.38%, turnover=8544891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=48.200000, depth_time=2026-10-31T13:45:30+00:00, book20_bid_proxy_usdt=523464, book20_ask_proxy_usdt=703920, funding_indicative=-0.000126, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=9625235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.161800, depth_time=2026-10-31T13:45:22+00:00, book20_bid_proxy_usdt=1368846, book20_ask_proxy_usdt=994686, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=6266442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=88.782000, depth_time=2026-10-31T13:45:15+00:00, book20_bid_proxy_usdt=192446, book20_ask_proxy_usdt=67763, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.22%, turnover=97026116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.020304, depth_time=2026-10-31T13:45:28+00:00, book20_bid_proxy_usdt=6270, book20_ask_proxy_usdt=5998, funding_indicative=0.000287, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=16070737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=55.120000, depth_time=2026-10-31T13:45:35+00:00, book20_bid_proxy_usdt=1084678, book20_ask_proxy_usdt=1606209, funding_indicative=-0.000054, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=5813702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.000005, depth_time=2026-10-31T13:45:33+00:00, book20_bid_proxy_usdt=24617, book20_ask_proxy_usdt=40193, funding_indicative=-0.000781, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=110281314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.032210, depth_time=2026-10-31T13:45:11+00:00, book20_bid_proxy_usdt=47419, book20_ask_proxy_usdt=52520, funding_indicative=-0.000471, next_funding_utc=2026-10-31T14:00:00+00:00, funding_cycle_h=1, 24h_change=-32.16%, turnover=12243972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.322470, depth_time=2026-10-31T13:45:18+00:00, book20_bid_proxy_usdt=98391, book20_ask_proxy_usdt=96143, funding_indicative=-0.000834, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.06%, turnover=6689424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T13:45:04+00:00, last15m_closed_end=2026-10-31T13:45+00:00, prior8high=0.398800, depth_time=2026-10-31T13:45:23+00:00, book20_bid_proxy_usdt=3093041, book20_ask_proxy_usdt=3222228, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=43154786. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

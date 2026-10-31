# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T12:15:35Z**
- feed_generated_utc: 2026-10-31T12:15:37+00:00
- source_sha256: `6825f9c8c475a768769a44c7aba7a2944804d9a5be66e3116466542bb57dabb4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T12:15+00:00, close=77580.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011600|-38.69|-66.85|-38.68|11010097|0.86|
|Q_USDT|0.031950|-32.70|-73.00|-32.69|12687802|3.13|
|IDOL_USDT|0.019038|-5.94|140.37|-5.93|16091631|0.52|
|TRX_USDT|0.318420|-5.09|-3.31|-5.08|6876512|0.63|
|HYPE_USDT|87.981000|-4.72|12.21|-4.71|93865810|0.11|
|BEAT_USDT|0.100600|-4.32|38.58|-4.31|7364387|4.97|
|WLD_USDT|0.395600|-3.95|-25.69|-3.94|44393325|2.53|
|FET_USDT|0.160700|-3.54|-14.20|-3.53|5655317|6.22|
|BTW_USDT|1.170700|-2.40|-31.23|-2.39|8494102|5.13|
|DASH_USDT|47.990000|-2.14|-10.88|-2.13|9613573|2.08|
|LTC_USDT|54.860000|-1.54|-6.14|-1.53|5978780|1.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011600|0.010360|0.011550|1.06|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100600|0.100420|0.100660|0.87|N|Y/N|N/N|Y|N|
|BTW_USDT|1.170700|1.118100|1.170700|2.63|N|N/Y|Y/Y|Y|N|
|DASH_USDT|47.990000|47.700000|47.990000|0.31|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160700|0.160800|0.160700|3.46|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|87.981000|86.889000|87.990000|0.91|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019038|0.017952|0.019036|0.30|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.860000|54.750000|54.860000|0.80|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031950|0.031370|0.031880|0.47|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318420|0.315970|0.318420|1.17|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395600|0.394200|0.395600|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.011724, depth_time=2026-10-31T12:15:08+00:00, book20_bid_proxy_usdt=10675, book20_ask_proxy_usdt=8916, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-38.69%, turnover=11010097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.104340, depth_time=2026-10-31T12:15:21+00:00, book20_bid_proxy_usdt=22613, book20_ask_proxy_usdt=14328, funding_indicative=0.000236, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=7364387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=1.204600, depth_time=2026-10-31T12:15:28+00:00, book20_bid_proxy_usdt=12666, book20_ask_proxy_usdt=9516, funding_indicative=-0.000284, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=8494102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=48.200000, depth_time=2026-10-31T12:15:29+00:00, book20_bid_proxy_usdt=631378, book20_ask_proxy_usdt=607121, funding_indicative=-0.000133, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=9613573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.162000, depth_time=2026-10-31T12:15:25+00:00, book20_bid_proxy_usdt=989273, book20_ask_proxy_usdt=1014904, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=5655317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=88.782000, depth_time=2026-10-31T12:15:19+00:00, book20_bid_proxy_usdt=113500, book20_ask_proxy_usdt=34160, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=93865810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.019922, depth_time=2026-10-31T12:15:13+00:00, book20_bid_proxy_usdt=3807, book20_ask_proxy_usdt=6626, funding_indicative=0.000229, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=16091631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=55.070000, depth_time=2026-10-31T12:15:34+00:00, book20_bid_proxy_usdt=967372, book20_ask_proxy_usdt=803018, funding_indicative=-0.000064, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=5978780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.033250, depth_time=2026-10-31T12:15:11+00:00, book20_bid_proxy_usdt=74439, book20_ask_proxy_usdt=72484, funding_indicative=-0.000551, next_funding_utc=2026-10-31T13:00:00+00:00, funding_cycle_h=1, 24h_change=-32.70%, turnover=12687802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.320970, depth_time=2026-10-31T12:15:16+00:00, book20_bid_proxy_usdt=73066, book20_ask_proxy_usdt=61527, funding_indicative=-0.001015, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=6876512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T12:15:04+00:00, last15m_closed_end=2026-10-31T12:15+00:00, prior8high=0.397100, depth_time=2026-10-31T12:15:23+00:00, book20_bid_proxy_usdt=3277573, book20_ask_proxy_usdt=2287158, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=44393325. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

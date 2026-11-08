# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T09:00:38Z**
- feed_generated_utc: 2026-11-08T09:00:40+00:00
- source_sha256: `f6a3a3cff23069724776b365108e87837b84da4b2ea652fa19f939b77847cac5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T09:00+00:00, close=75900.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T09:00+00:00, close=75900.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.427100|-3.15|-12.85|-3.38|7394557|2.34|
|WLD_USDT|0.327700|-2.58|-18.96|-2.81|23307880|3.05|
|ENA_USDT|0.154130|-2.56|-20.55|-2.79|29104439|0.65|
|QNT_USDT|195.170000|-1.98|-2.92|-2.21|42516034|1.02|
|PUMPFUN_USDT|0.003681|-1.63|-11.97|-1.86|16924433|2.72|
|LINK_USDT|10.731000|-1.59|-7.25|-1.82|64728422|0.93|
|ADA_USDT|0.180100|-1.36|-6.97|-1.59|9600319|5.55|
|ONDO_USDT|0.359500|-1.29|-12.82|-1.52|8189144|2.78|
|AVAX_USDT|8.160000|-1.12|-4.39|-1.35|7529216|1.23|
|SUI_USDT|0.851400|-1.09|-5.60|-1.32|22436070|2.35|
|AAVE_USDT|130.320000|-1.08|-3.82|-1.31|10352568|0.77|
|DOGE_USDT|0.071120|-1.01|-5.97|-1.24|38167588|1.41|
|HYPE_USDT|77.146000|-0.88|-11.87|-1.11|20717019|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.320000|129.910000|130.320000|1.27|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180100|0.179600|0.180100|0.53|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.160000|8.155000|8.160000|1.26|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.071120|0.070950|0.071090|4.29|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154130|0.153560|0.154010|1.90|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|77.146000|77.065000|77.146000|0.31|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.731000|10.708000|10.731000|0.72|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359500|0.357600|0.359500|0.22|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003681|0.003635|0.003681|1.04|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.170000|194.160000|195.170000|0.61|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.851400|0.849200|0.851300|1.10|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.427100|0.427100|0.427100|1.17|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327700|0.327600|0.327700|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=130.820000, depth_time=2026-11-08T09:00:27+00:00, book20_bid_proxy_usdt=532797, book20_ask_proxy_usdt=409085, funding_indicative=0.000016, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=10352568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.180600, depth_time=2026-11-08T09:00:22+00:00, book20_bid_proxy_usdt=10556530, book20_ask_proxy_usdt=9302573, funding_indicative=-0.000007, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=9600319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=8.196000, depth_time=2026-11-08T09:00:23+00:00, book20_bid_proxy_usdt=2329128, book20_ask_proxy_usdt=1930644, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=7529216. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.071310, depth_time=2026-11-08T09:00:35+00:00, book20_bid_proxy_usdt=4665020, book20_ask_proxy_usdt=5217121, funding_indicative=0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=38167588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.154850, depth_time=2026-11-08T09:00:12+00:00, book20_bid_proxy_usdt=422199, book20_ask_proxy_usdt=146496, funding_indicative=0.000034, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=29104439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=77.401000, depth_time=2026-11-08T09:00:36+00:00, book20_bid_proxy_usdt=134175, book20_ask_proxy_usdt=140144, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=20717019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=10.753000, depth_time=2026-11-08T09:00:15+00:00, book20_bid_proxy_usdt=478879, book20_ask_proxy_usdt=546894, funding_indicative=0.000068, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=64728422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.360600, depth_time=2026-11-08T09:00:19+00:00, book20_bid_proxy_usdt=1707902, book20_ask_proxy_usdt=1728006, funding_indicative=0.000017, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=8189144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.003690, depth_time=2026-11-08T09:00:16+00:00, book20_bid_proxy_usdt=2406607, book20_ask_proxy_usdt=2029778, funding_indicative=0.000038, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=16924433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=196.140000, depth_time=2026-11-08T09:00:15+00:00, book20_bid_proxy_usdt=112201, book20_ask_proxy_usdt=61835, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=42516034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.855500, depth_time=2026-11-08T09:00:29+00:00, book20_bid_proxy_usdt=1244574, book20_ask_proxy_usdt=1688658, funding_indicative=-0.000022, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=22436070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.432100, depth_time=2026-11-08T09:00:07+00:00, book20_bid_proxy_usdt=384655, book20_ask_proxy_usdt=392375, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=7394557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T09:00:02+00:00, last15m_closed_end=2026-11-08T09:00+00:00, prior8high=0.331200, depth_time=2026-11-08T09:00:08+00:00, book20_bid_proxy_usdt=4477986, book20_ask_proxy_usdt=3500181, funding_indicative=-0.000156, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=23307880. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

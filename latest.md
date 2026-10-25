# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T14:30:40Z**
- feed_generated_utc: 2026-10-25T14:30:43+00:00
- source_sha256: `7cf29847b187e61cae66c329a8d1fdf07e3003b7ed542936f63bda7996d45b3a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T14:30+00:00, close=80303.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T14:00+00:00, close=80346.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.046290|-31.32|49.56|-31.99|5855301|2.16|
|STRK_USDT|0.044670|-4.40|-32.47|-5.07|10613864|2.24|
|WLD_USDT|0.446600|-3.33|-9.88|-4.00|95765394|2.24|
|BTW_USDT|1.687100|-3.11|-25.65|-3.78|12389771|0.59|
|SUI_USDT|0.907800|-1.85|-7.53|-2.52|71717924|1.10|
|DOT_USDT|1.021400|-1.70|-8.59|-2.37|12688194|0.98|
|APT_USDT|0.690800|-1.58|-13.37|-2.25|5915842|1.45|
|PENGU_USDT|0.007345|-1.31|-1.44|-1.98|5985973|1.36|
|SEI_USDT|0.052250|-1.19|-15.73|-1.86|6175437|1.91|
|PUMPFUN_USDT|0.004150|-0.47|-5.93|-1.14|15095843|2.41|
|LINK_USDT|11.332000|-0.43|-4.82|-1.10|48427510|0.88|
|OP_USDT|0.109630|-0.43|-15.01|-1.10|6237528|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.690800|0.691300|0.690800|0.35|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.687100|1.657000|1.687300|0.85|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.021400|1.021400|1.021400|0.34|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.332000|11.325000|11.332000|0.58|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109630|0.109710|0.109630|1.23|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046290|0.045450|0.046460|1.03|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007345|0.007340|0.007345|0.25|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004150|0.004140|0.004150|1.21|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052250|0.052220|0.052250|0.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044670|0.045200|0.044670|3.67|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|0.907800|0.909100|0.907800|1.60|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.446600|0.445400|0.446600|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.698000, depth_time=2026-10-25T14:30:23+00:00, book20_bid_proxy_usdt=202198, book20_ask_proxy_usdt=132679, funding_indicative=-0.000123, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=5915842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=1.701100, depth_time=2026-10-25T14:30:16+00:00, book20_bid_proxy_usdt=13465, book20_ask_proxy_usdt=9269, funding_indicative=-0.008891, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=12389771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=1.031100, depth_time=2026-10-25T14:30:20+00:00, book20_bid_proxy_usdt=330120, book20_ask_proxy_usdt=300283, funding_indicative=-0.000112, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=12688194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=11.417000, depth_time=2026-10-25T14:30:36+00:00, book20_bid_proxy_usdt=505486, book20_ask_proxy_usdt=479816, funding_indicative=-0.000054, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.43%, turnover=48427510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.110530, depth_time=2026-10-25T14:30:38+00:00, book20_bid_proxy_usdt=124318, book20_ask_proxy_usdt=102096, funding_indicative=-0.000003, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.43%, turnover=6237528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.048120, depth_time=2026-10-25T14:30:08+00:00, book20_bid_proxy_usdt=87458, book20_ask_proxy_usdt=103996, funding_indicative=-0.000974, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-31.32%, turnover=5855301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T14:30:03+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.007403, depth_time=2026-10-25T14:30:27+00:00, book20_bid_proxy_usdt=294382, book20_ask_proxy_usdt=199419, funding_indicative=-0.000047, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=5985973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.004207, depth_time=2026-10-25T14:30:33+00:00, book20_bid_proxy_usdt=2371164, book20_ask_proxy_usdt=2522406, funding_indicative=0.000007, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.47%, turnover=15095843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.052650, depth_time=2026-10-25T14:30:30+00:00, book20_bid_proxy_usdt=322789, book20_ask_proxy_usdt=357186, funding_indicative=-0.000016, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=6175437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.045820, depth_time=2026-10-25T14:30:10+00:00, book20_bid_proxy_usdt=801084, book20_ask_proxy_usdt=901010, funding_indicative=0.000019, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.40%, turnover=10613864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.919500, depth_time=2026-10-25T14:30:18+00:00, book20_bid_proxy_usdt=1178510, book20_ask_proxy_usdt=1906471, funding_indicative=-0.000059, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=71717924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T14:30:02+00:00, last15m_closed_end=2026-10-25T14:30+00:00, prior8high=0.452300, depth_time=2026-10-25T14:30:13+00:00, book20_bid_proxy_usdt=2252712, book20_ask_proxy_usdt=1550128, funding_indicative=-0.000066, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=95765394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

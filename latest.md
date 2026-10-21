# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T10:15:30Z**
- feed_generated_utc: 2026-10-21T10:15:33+00:00
- source_sha256: `1a491cb51b186ce0426eda4b9e3f2dbb41772f977aedcb7e5cf9069d4777e1ce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T10:15+00:00, close=83287.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T10:00+00:00, close=83402.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.048994|-24.19|202.86|-25.04|6647422|4.89|
|BAT_USDT|0.181970|-15.66|2.58|-16.51|10933789|0.55|
|BR_USDT|0.578640|-11.07|33.63|-11.92|25055743|1.90|
|BTW_USDT|1.735500|-6.16|-11.11|-7.01|25187881|4.62|
|Q_USDT|0.118287|-3.63|187.61|-4.48|5618527|9.89|
|SILVER_USDT|57.350000|-1.03|-3.43|-1.88|216813835|1.74|
|TIA_USDT|0.616600|-0.97|6.80|-1.82|45543089|1.62|
|DOT_USDT|1.147200|-0.89|-0.83|-1.74|14207318|0.87|
|XAU_USDT|4122.900000|-0.39|-1.02|-1.24|382804834|0.02|
|XAUT_USDT|4115.800000|-0.29|-0.98|-1.14|147224922|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.048994|0.042549|0.048994|0.95|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.181970|0.181440|0.181970|0.94|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.578640|0.566870|0.578740|1.27|N|Y/Y|N/N|N|N|
|BTW_USDT|1.735500|2.028000|1.740600|5.36|Y|N/N|N/N|N|N|
|DOT_USDT|1.147200|1.150300|1.147200|4.09|Y|Y/N|N/N|N|N|
|Q_USDT|0.118287|0.119133|0.118113|0.65|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.350000|57.310000|57.350000|2.53|N|Y/Y|N/N|N|N|
|TIA_USDT|0.616600|0.618400|0.616600|2.64|Y|Y/N|N/Y|N|N|
|XAUT_USDT|4115.800000|4117.940000|4115.900000|0.45|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4122.900000|4125.700000|4123.140000|1.17|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=0.051865, depth_time=2026-10-21T10:15:08+00:00, book20_bid_proxy_usdt=9688, book20_ask_proxy_usdt=9235, funding_indicative=0.000048, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.19%, turnover=6647422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=0.190160, depth_time=2026-10-21T10:15:10+00:00, book20_bid_proxy_usdt=23207, book20_ask_proxy_usdt=27717, funding_indicative=-0.000110, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.66%, turnover=10933789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=0.627970, depth_time=2026-10-21T10:15:10+00:00, book20_bid_proxy_usdt=2584, book20_ask_proxy_usdt=2448, funding_indicative=-0.000022, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.07%, turnover=25055743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=2.153000, depth_time=2026-10-21T10:15:15+00:00, book20_bid_proxy_usdt=11033, book20_ask_proxy_usdt=14962, funding_indicative=-0.000561, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.16%, turnover=25187881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=1.166200, depth_time=2026-10-21T10:15:22+00:00, book20_bid_proxy_usdt=411113, book20_ask_proxy_usdt=257971, funding_indicative=-0.000283, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=14207318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=0.126485, depth_time=2026-10-21T10:15:18+00:00, book20_bid_proxy_usdt=19128, book20_ask_proxy_usdt=15151, funding_indicative=0.000005, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=5618527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=57.610000, depth_time=2026-10-21T10:15:20+00:00, book20_bid_proxy_usdt=35663931, book20_ask_proxy_usdt=36168823, funding_indicative=0.000034, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=216813835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=0.642000, depth_time=2026-10-21T10:15:22+00:00, book20_bid_proxy_usdt=242918, book20_ask_proxy_usdt=357029, funding_indicative=-0.000089, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.97%, turnover=45543089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=4126.350000, depth_time=2026-10-21T10:15:29+00:00, book20_bid_proxy_usdt=113655, book20_ask_proxy_usdt=129588, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.29%, turnover=147224922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T10:15:01+00:00, last15m_closed_end=2026-10-21T10:15+00:00, prior8high=4133.460000, depth_time=2026-10-21T10:15:27+00:00, book20_bid_proxy_usdt=231550, book20_ask_proxy_usdt=2338781, funding_indicative=0.000064, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=382804834. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

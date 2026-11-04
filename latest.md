# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T05:00:27Z**
- feed_generated_utc: 2026-11-04T05:00:29+00:00
- source_sha256: `e5dc6660a248c384e9464f24019ff5cc7a7ebf995268b5da2ddb1408e832f9ec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T05:00+00:00, close=77357.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T05:00+00:00, close=77357.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037010|-31.22|-22.11|-30.85|11581828|2.70|
|AKE_USDT|0.003200|-23.00|-84.85|-22.63|11956786|6.26|
|ICNT_USDT|0.210400|-11.78|18.66|-11.41|5150302|4.75|
|HOT_USDT|0.000485|-9.99|40.30|-9.62|8175749|6.19|
|TRUMPOFFICIAL_USDT|1.514000|-5.72|-10.30|-5.35|8125961|6.59|
|XPL_USDT|0.061980|-3.23|-16.03|-2.86|7251405|1.61|
|XLM_USDT|0.160930|-2.34|-4.89|-1.97|37271414|1.24|
|Q_USDT|0.027740|-1.87|-56.37|-1.50|7333637|3.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037010|0.036380|0.037030|0.66|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003200|0.003311|0.003207|2.82|Y|Y/Y|Y/Y|Y|Y|
|HOT_USDT|0.000485|0.000458|0.000485|0.27|N|Y/Y|N/N|Y|N|
|ICNT_USDT|0.210400|0.209800|0.210400|0.73|N|Y/Y|N/N|Y|N|
|Q_USDT|0.027740|0.027630|0.027740|0.74|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.514000|1.475000|1.513000|0.56|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.160930|0.156990|0.160850|0.87|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061980|0.060070|0.061950|0.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T05:00:02+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.038690, depth_time=2026-11-04T05:00:08+00:00, book20_bid_proxy_usdt=30352, book20_ask_proxy_usdt=21706, funding_indicative=0.000047, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.22%, turnover=11581828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T05:00:02+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.003654, depth_time=2026-11-04T05:00:12+00:00, book20_bid_proxy_usdt=32108, book20_ask_proxy_usdt=26134, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.00%, turnover=11956786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T05:00:02+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.000494, depth_time=2026-11-04T05:00:16+00:00, book20_bid_proxy_usdt=66669, book20_ask_proxy_usdt=79639, funding_indicative=-0.000926, next_funding_utc=2026-11-04T06:00:00+00:00, funding_cycle_h=1, 24h_change=-9.99%, turnover=8175749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-11-04T05:00:02+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.220500, depth_time=2026-11-04T05:00:13+00:00, book20_bid_proxy_usdt=136454, book20_ask_proxy_usdt=136421, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.78%, turnover=5150302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T05:00:02+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.029150, depth_time=2026-11-04T05:00:26+00:00, book20_bid_proxy_usdt=53423, book20_ask_proxy_usdt=41024, funding_indicative=-0.000587, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=7333637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T05:00:03+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=1.518000, depth_time=2026-11-04T05:00:19+00:00, book20_bid_proxy_usdt=2024046, book20_ask_proxy_usdt=2112959, funding_indicative=-0.000213, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.72%, turnover=8125961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T05:00:03+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.160540, depth_time=2026-11-04T05:00:24+00:00, book20_bid_proxy_usdt=127966, book20_ask_proxy_usdt=169876, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=37271414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T05:00:03+00:00, last15m_closed_end=2026-11-04T05:00+00:00, prior8high=0.061950, depth_time=2026-11-04T05:00:21+00:00, book20_bid_proxy_usdt=403758, book20_ask_proxy_usdt=414126, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=7251405. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T15:15:26Z**
- feed_generated_utc: 2026-10-29T15:15:29+00:00
- source_sha256: `a78662900d3131f81878ae1d680cef8e4a5eb71036176884aab4365386561b45`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T15:15+00:00, close=81557.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T15:00+00:00, close=81149.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.039470|-36.61|-66.02|-37.91|34303522|7.60|
|EVAA_USDT|1.164000|-21.61|106.52|-22.91|17004050|6.00|
|BLESS_USDT|0.009688|-11.58|20.37|-12.88|8148878|9.30|
|DASH_USDT|51.120000|-3.61|-4.03|-4.91|16223735|1.96|
|BTW_USDT|1.685900|-2.99|14.70|-4.29|9237802|1.78|
|SILVER_USDT|52.590000|-2.01|-8.79|-3.31|545432597|1.90|
|XAU_USDT|4031.960000|-0.43|-2.59|-1.73|616622178|0.03|
|XAUT_USDT|4021.410000|-0.38|-2.63|-1.68|262227256|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009688|0.009476|0.009696|0.82|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.685900|1.606100|1.686400|1.10|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.120000|50.040000|51.120000|7.17|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.164000|1.161100|1.168200|0.65|N|Y/Y|N/N|Y|N|
|Q_USDT|0.039470|0.040040|0.039390|2.23|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|52.590000|52.110000|52.590000|1.07|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4021.410000|4015.260000|4020.970000|1.95|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4031.960000|4025.280000|4031.490000|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=0.009702, depth_time=2026-10-29T15:15:13+00:00, book20_bid_proxy_usdt=9584, book20_ask_proxy_usdt=4224, funding_indicative=0.000323, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.58%, turnover=8148878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=1.791000, depth_time=2026-10-29T15:15:17+00:00, book20_bid_proxy_usdt=10968, book20_ask_proxy_usdt=16388, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=9237802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=51.010000, depth_time=2026-10-29T15:15:16+00:00, book20_bid_proxy_usdt=530999, book20_ask_proxy_usdt=569030, funding_indicative=0.000007, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=16223735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=1.249100, depth_time=2026-10-29T15:15:11+00:00, book20_bid_proxy_usdt=13073, book20_ask_proxy_usdt=7754, funding_indicative=0.000169, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.61%, turnover=17004050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=0.042860, depth_time=2026-10-29T15:15:09+00:00, book20_bid_proxy_usdt=74358, book20_ask_proxy_usdt=41348, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.61%, turnover=34303522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=52.890000, depth_time=2026-10-29T15:15:21+00:00, book20_bid_proxy_usdt=49467028, book20_ask_proxy_usdt=48085648, funding_indicative=0.000082, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=545432597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=4033.370000, depth_time=2026-10-29T15:15:23+00:00, book20_bid_proxy_usdt=204716, book20_ask_proxy_usdt=223081, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=262227256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-29T15:15:02+00:00, last15m_closed_end=2026-10-29T15:15+00:00, prior8high=4044.990000, depth_time=2026-10-29T15:15:23+00:00, book20_bid_proxy_usdt=548566, book20_ask_proxy_usdt=4150561, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.43%, turnover=616622178. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T19:45:25Z**
- feed_generated_utc: 2026-10-14T19:45:27+00:00
- source_sha256: `c92442ffc7fa21e0af775f6dd506e77b346d54a70c3e37cfcdca8c54ccf76679`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T19:45+00:00, close=81701, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T19:00+00:00, close=81679.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.155600|-9.38|74.35|-9.50|60896385|3.71|
|FET_USDT|0.194400|-4.65|-14.17|-4.77|10410658|5.14|
|BAT_USDT|0.167810|-3.78|69.23|-3.90|35826209|1.79|
|S_USDT|0.052900|-3.44|32.78|-3.56|6916916|1.89|
|STRK_USDT|0.075620|-2.02|52.89|-2.14|24649550|1.32|
|NEAR_USDT|4.773000|-1.40|-5.18|-1.52|179036654|4.19|
|LDO_USDT|0.401100|-1.15|-6.15|-1.27|5043461|2.49|
|COPPER_USDT|6.611000|-0.94|-1.10|-1.06|6464785|1.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.167810|0.168650|0.167760|1.24|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.155600|2.064400|2.148500|1.85|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.611000|6.616000|6.611000|0.99|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194400|0.197400|0.194500|3.09|Y|Y/Y|Y/Y|Y|Y|
|LDO_USDT|0.401100|0.400200|0.401100|0.45|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.773000|4.776000|4.770000|0.69|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075620|0.075110|0.075620|2.06|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052900|0.052330|0.052880|0.19|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=0.173100, depth_time=2026-10-14T19:45:12+00:00, book20_bid_proxy_usdt=25411, book20_ask_proxy_usdt=54158, funding_indicative=0.000016, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=35826209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=2.279300, depth_time=2026-10-14T19:45:08+00:00, book20_bid_proxy_usdt=7348, book20_ask_proxy_usdt=13628, funding_indicative=-0.000005, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.38%, turnover=60896385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T19:45:00+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=6.659000, depth_time=2026-10-14T19:45:23+00:00, book20_bid_proxy_usdt=1533987, book20_ask_proxy_usdt=1561642, funding_indicative=0.000000, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=6464785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=0.207200, depth_time=2026-10-14T19:45:08+00:00, book20_bid_proxy_usdt=1476978, book20_ask_proxy_usdt=1161903, funding_indicative=0.000038, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.65%, turnover=10410658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=0.406000, depth_time=2026-10-14T19:45:20+00:00, book20_bid_proxy_usdt=510070, book20_ask_proxy_usdt=555443, funding_indicative=-0.000124, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=5043461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=4.853000, depth_time=2026-10-14T19:45:19+00:00, book20_bid_proxy_usdt=2122527, book20_ask_proxy_usdt=1916721, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=179036654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=0.076310, depth_time=2026-10-14T19:45:17+00:00, book20_bid_proxy_usdt=158374, book20_ask_proxy_usdt=300715, funding_indicative=0.000035, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=24649550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T19:45:03+00:00, last15m_closed_end=2026-10-14T19:45+00:00, prior8high=0.053070, depth_time=2026-10-14T19:45:11+00:00, book20_bid_proxy_usdt=160753, book20_ask_proxy_usdt=165943, funding_indicative=-0.000089, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=6916916. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

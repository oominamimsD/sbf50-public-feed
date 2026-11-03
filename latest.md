# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T11:45:40Z**
- feed_generated_utc: 2026-11-03T11:45:43+00:00
- source_sha256: `f04bceb948bc88635e50cd84dc8edf6c6a2461d9490cebc551aff9e40518bfc7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T11:45+00:00, close=77068.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T11:00+00:00, close=77103.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004480|-18.57|-85.44|-18.04|12944425|2.23|
|BTW_USDT|0.937000|-14.56|-21.63|-14.03|10707610|1.07|
|XPL_USDT|0.064560|-7.21|-13.09|-6.68|11565720|1.55|
|ZEC_USDT|1180.260000|-5.88|-5.40|-5.35|1824441846|0.09|
|NEAR_USDT|3.853000|-3.91|-15.74|-3.38|77931550|5.19|
|SILVER_USDT|49.160000|-3.72|-9.34|-3.19|434180125|2.03|
|TIA_USDT|0.440200|-3.65|-17.82|-3.12|12913250|2.27|
|DASH_USDT|45.810000|-2.94|-12.27|-2.41|9262006|2.18|
|TRUMPOFFICIAL_USDT|1.588000|-2.93|-5.97|-2.40|9433202|6.30|
|XLM_USDT|0.162850|-2.83|-3.97|-2.30|34599392|1.84|
|ENA_USDT|0.170630|-2.51|-18.89|-1.98|68814464|0.59|
|FARTCOIN_USDT|0.117100|-1.81|-8.75|-1.28|9946773|0.85|
|APT_USDT|0.617200|-1.57|-12.07|-1.04|5381843|3.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004480|0.004436|0.004479|0.92|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.617200|0.611100|0.617100|1.11|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.937000|0.870600|0.936700|3.66|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.810000|45.630000|45.800000|3.83|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170630|0.169020|0.170600|0.87|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117100|0.115930|0.117050|1.18|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.853000|3.801000|3.853000|1.38|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.160000|48.920000|49.160000|0.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.440200|0.436200|0.440300|1.92|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.588000|1.581000|1.588000|2.25|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162850|0.161580|0.162860|1.06|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064560|0.063400|0.064560|0.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1180.260000|1137.920000|1180.450000|1.75|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.004638, depth_time=2026-11-03T11:45:08+00:00, book20_bid_proxy_usdt=48500, book20_ask_proxy_usdt=51764, funding_indicative=-0.001891, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.57%, turnover=12944425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.619600, depth_time=2026-11-03T11:45:37+00:00, book20_bid_proxy_usdt=183411, book20_ask_proxy_usdt=141805, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=5381843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.960600, depth_time=2026-11-03T11:45:10+00:00, book20_bid_proxy_usdt=21046, book20_ask_proxy_usdt=47064, funding_indicative=-0.000247, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.56%, turnover=10707610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=45.990000, depth_time=2026-11-03T11:45:23+00:00, book20_bid_proxy_usdt=653658, book20_ask_proxy_usdt=620873, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=9262006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.171360, depth_time=2026-11-03T11:45:33+00:00, book20_bid_proxy_usdt=242030, book20_ask_proxy_usdt=310545, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=68814464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.117380, depth_time=2026-11-03T11:45:34+00:00, book20_bid_proxy_usdt=83695, book20_ask_proxy_usdt=70547, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=9946773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=3.868000, depth_time=2026-11-03T11:45:16+00:00, book20_bid_proxy_usdt=2960739, book20_ask_proxy_usdt=5121048, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=77931550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=49.240000, depth_time=2026-11-03T11:45:20+00:00, book20_bid_proxy_usdt=89069998, book20_ask_proxy_usdt=46216738, funding_indicative=0.000077, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=434180125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.442100, depth_time=2026-11-03T11:45:22+00:00, book20_bid_proxy_usdt=345168, book20_ask_proxy_usdt=391602, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=12913250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=1.602000, depth_time=2026-11-03T11:45:25+00:00, book20_bid_proxy_usdt=2194996, book20_ask_proxy_usdt=2259712, funding_indicative=-0.000019, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=9433202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.163180, depth_time=2026-11-03T11:45:30+00:00, book20_bid_proxy_usdt=241433, book20_ask_proxy_usdt=206858, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=34599392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=0.064850, depth_time=2026-11-03T11:45:12+00:00, book20_bid_proxy_usdt=671900, book20_ask_proxy_usdt=387544, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.21%, turnover=11565720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T11:45:02+00:00, last15m_closed_end=2026-11-03T11:45+00:00, prior8high=1178.220000, depth_time=2026-11-03T11:45:15+00:00, book20_bid_proxy_usdt=374882, book20_ask_proxy_usdt=546569, funding_indicative=0.000016, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.88%, turnover=1824441846. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

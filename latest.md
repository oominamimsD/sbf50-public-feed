# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T09:30:30Z**
- feed_generated_utc: 2026-10-20T09:30:32+00:00
- source_sha256: `c28858217960960a9f5da5ac04950ca78ec356c41388ec41c8e85bc0cfe28675`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T09:30+00:00, close=81412, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T09:00+00:00, close=81498.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.070869|-18.57|325.33|-17.96|9666721|4.38|
|BTW_USDT|1.604500|-8.41|-8.61|-7.80|33362616|1.25|
|SAND_USDT|0.056580|-4.32|-8.87|-3.71|5823239|1.77|
|NEAR_USDT|4.712000|-3.91|-15.08|-3.30|163420328|2.12|
|ATOM_USDT|1.718000|-3.26|-6.01|-2.65|5175669|5.82|
|ARB_USDT|0.190070|-2.84|0.84|-2.23|95936509|0.53|
|UNI_USDT|7.133000|-2.12|-3.84|-1.51|10285109|1.40|
|TAO_USDT|262.650000|-2.10|-8.25|-1.49|58646005|1.14|
|QNT_USDT|191.870000|-1.95|-15.98|-1.34|80677785|0.52|
|SEI_USDT|0.059680|-1.63|-10.07|-1.02|6734358|1.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.070869|0.066550|0.070861|1.60|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190070|0.188850|0.190070|0.40|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.718000|1.718000|1.718000|2.08|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.604500|1.486000|1.604400|2.04|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.712000|4.710000|4.712000|0.74|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.870000|189.730000|191.870000|0.91|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056580|0.056360|0.056580|1.26|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059680|0.059530|0.059680|0.32|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.650000|261.940000|262.650000|0.89|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.133000|7.099000|7.133000|0.95|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=0.079107, depth_time=2026-10-20T09:30:07+00:00, book20_bid_proxy_usdt=8224, book20_ask_proxy_usdt=6944, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.57%, turnover=9666721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=0.196300, depth_time=2026-10-20T09:30:20+00:00, book20_bid_proxy_usdt=72365, book20_ask_proxy_usdt=77146, funding_indicative=0.000058, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=95936509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=1.743000, depth_time=2026-10-20T09:30:17+00:00, book20_bid_proxy_usdt=1488123, book20_ask_proxy_usdt=1118571, funding_indicative=0.000094, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=5175669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=1.719800, depth_time=2026-10-20T09:30:10+00:00, book20_bid_proxy_usdt=37862, book20_ask_proxy_usdt=20327, funding_indicative=-0.004332, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.41%, turnover=33362616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=4.799000, depth_time=2026-10-20T09:30:15+00:00, book20_bid_proxy_usdt=6418952, book20_ask_proxy_usdt=2557774, funding_indicative=0.000040, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=163420328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=193.710000, depth_time=2026-10-20T09:30:26+00:00, book20_bid_proxy_usdt=114249, book20_ask_proxy_usdt=66822, funding_indicative=0.000039, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=80677785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T09:30:01+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=0.057110, depth_time=2026-10-20T09:30:09+00:00, book20_bid_proxy_usdt=757798, book20_ask_proxy_usdt=853606, funding_indicative=-0.001488, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=5823239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T09:30:01+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=0.060340, depth_time=2026-10-20T09:30:27+00:00, book20_bid_proxy_usdt=269138, book20_ask_proxy_usdt=203845, funding_indicative=0.000013, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=6734358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=265.210000, depth_time=2026-10-20T09:30:24+00:00, book20_bid_proxy_usdt=108037, book20_ask_proxy_usdt=127929, funding_indicative=0.000042, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=58646005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T09:30:00+00:00, last15m_closed_end=2026-10-20T09:30+00:00, prior8high=7.196000, depth_time=2026-10-20T09:30:21+00:00, book20_bid_proxy_usdt=1758207, book20_ask_proxy_usdt=2093317, funding_indicative=0.000075, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=10285109. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

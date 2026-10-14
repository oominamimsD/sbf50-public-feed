# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T10:30:25Z**
- feed_generated_utc: 2026-10-14T10:30:27+00:00
- source_sha256: `ce10b28a8e8481705fb0b1176e7f72ac2d23e1c35c4712515586917502dd666b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T10:30+00:00, close=83305.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T10:00+00:00, close=83219.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078300|-9.92|50.02|-9.82|29322472|2.56|
|TIA_USDT|0.542100|-6.09|13.81|-5.99|36878759|1.84|
|W_USDT|0.015947|-5.09|9.88|-4.99|6832248|3.76|
|UNI_USDT|7.355000|-2.86|-15.11|-2.76|19089210|1.36|
|DOT_USDT|1.133800|-1.99|-5.62|-1.89|20302787|0.88|
|ICP_USDT|3.072000|-1.28|-9.70|-1.18|9770407|3.25|
|SILVER_USDT|58.650000|-1.24|-4.43|-1.14|258433987|1.71|
|XLM_USDT|0.188810|-1.13|-11.63|-1.03|9935336|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.133800|1.129300|1.133800|0.75|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.072000|3.053000|3.072000|0.68|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|58.650000|58.570000|58.650000|1.57|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.078300|0.078190|0.078290|0.79|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.542100|0.543000|0.542100|1.01|N|Y/Y|Y/N|Y|N|
|UNI_USDT|7.355000|7.328000|7.355000|0.52|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.015947|0.015659|0.015947|0.76|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.188810|0.188210|0.188810|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=1.159500, depth_time=2026-10-14T10:30:16+00:00, book20_bid_proxy_usdt=365346, book20_ask_proxy_usdt=341512, funding_indicative=0.000023, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=20302787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=3.131000, depth_time=2026-10-14T10:30:17+00:00, book20_bid_proxy_usdt=832639, book20_ask_proxy_usdt=705048, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=9770407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=59.010000, depth_time=2026-10-14T10:30:21+00:00, book20_bid_proxy_usdt=49764169, book20_ask_proxy_usdt=47225633, funding_indicative=0.000094, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=258433987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=0.082970, depth_time=2026-10-14T10:30:07+00:00, book20_bid_proxy_usdt=269666, book20_ask_proxy_usdt=309384, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.92%, turnover=29322472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=0.560800, depth_time=2026-10-14T10:30:10+00:00, book20_bid_proxy_usdt=102085, book20_ask_proxy_usdt=221404, funding_indicative=-0.000014, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.09%, turnover=36878759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=7.461000, depth_time=2026-10-14T10:30:13+00:00, book20_bid_proxy_usdt=1281932, book20_ask_proxy_usdt=986765, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=19089210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=0.016686, depth_time=2026-10-14T10:30:12+00:00, book20_bid_proxy_usdt=31229, book20_ask_proxy_usdt=28089, funding_indicative=-0.000324, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=6832248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T10:30:01+00:00, last15m_closed_end=2026-10-14T10:30+00:00, prior8high=0.191460, depth_time=2026-10-14T10:30:23+00:00, book20_bid_proxy_usdt=178605, book20_ask_proxy_usdt=202585, funding_indicative=-0.000106, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=9935336. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

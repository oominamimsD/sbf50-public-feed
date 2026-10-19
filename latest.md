# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T01:45:17Z**
- feed_generated_utc: 2026-10-19T01:45:19+00:00
- source_sha256: `eb1d3a7925b35085a3b43f9866e7437766751226264aaca1402b76dc0988d25a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T01:45+00:00, close=82489.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T01:00+00:00, close=82269.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.064298|-4.78|263.57|-6.44|9804855|4.50|
|HBAR_USDT|0.084550|-1.43|-9.84|-3.09|50896528|1.18|
|STRK_USDT|0.060780|-1.26|-49.03|-2.92|17134665|1.65|
|BTW_USDT|2.297100|-0.36|36.55|-2.02|22618538|4.34|
|ICNT_USDT|0.178800|-0.33|68.67|-1.99|7753265|5.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.064298|0.061150|0.064275|0.85|N|Y/Y|N/N|N|N|
|BTW_USDT|2.297100|2.230700|2.297100|0.75|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084550|0.084210|0.084550|0.75|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.178800|0.176000|0.178800|1.75|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060780|0.059770|0.060770|0.69|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T01:45:00+00:00, last15m_closed_end=2026-10-19T01:45+00:00, prior8high=0.068360, depth_time=2026-10-19T01:45:07+00:00, book20_bid_proxy_usdt=2556, book20_ask_proxy_usdt=3589, funding_indicative=0.000209, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=9804855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T01:45:00+00:00, last15m_closed_end=2026-10-19T01:45+00:00, prior8high=2.448800, depth_time=2026-10-19T01:45:14+00:00, book20_bid_proxy_usdt=18207, book20_ask_proxy_usdt=7382, funding_indicative=-0.000417, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.36%, turnover=22618538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T01:45:00+00:00, last15m_closed_end=2026-10-19T01:45+00:00, prior8high=0.085740, depth_time=2026-10-19T01:45:10+00:00, book20_bid_proxy_usdt=817599, book20_ask_proxy_usdt=530238, funding_indicative=-0.000024, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=50896528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T01:45:00+00:00, last15m_closed_end=2026-10-19T01:45+00:00, prior8high=0.193800, depth_time=2026-10-19T01:45:17+00:00, book20_bid_proxy_usdt=209202, book20_ask_proxy_usdt=114511, funding_indicative=-0.000003, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.33%, turnover=7753265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T01:45:00+00:00, last15m_closed_end=2026-10-19T01:45+00:00, prior8high=0.061290, depth_time=2026-10-19T01:45:12+00:00, book20_bid_proxy_usdt=541960, book20_ask_proxy_usdt=236877, funding_indicative=0.000031, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=17134665. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.

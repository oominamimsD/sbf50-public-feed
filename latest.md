# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T01:30:22Z**
- feed_generated_utc: 2026-10-19T01:30:24+00:00
- source_sha256: `b02d7188ef35c6cdbc5d02b6a329cc3806f60754e4485f6732e64960f4137b9b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T01:30+00:00, close=82434.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T01:00+00:00, close=82269.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.111020|-8.98|291.99|-10.57|9745289|5.68|
|AGT_USDT|0.064447|-4.56|264.41|-6.15|9773101|4.19|
|HBAR_USDT|0.084270|-1.76|-10.14|-3.35|50733705|1.19|
|ICNT_USDT|0.176600|-1.56|66.60|-3.15|7721221|5.66|
|STRK_USDT|0.060850|-1.15|-48.98|-2.74|17027149|1.64|
|BTW_USDT|2.309400|0.17|37.28|-1.42|22483494|3.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.064447|0.060885|0.064428|0.86|N|Y/Y|N/N|N|N|
|BTW_USDT|2.309400|2.230700|2.309400|0.52|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084270|0.084210|0.084270|0.62|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.176600|0.178600|0.176600|2.21|Y|Y/Y|N/N|N|N|
|Q_USDT|0.111020|0.107553|0.111020|3.24|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060850|0.059540|0.060850|0.85|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=0.068584, depth_time=2026-10-19T01:30:10+00:00, book20_bid_proxy_usdt=2848, book20_ask_proxy_usdt=1728, funding_indicative=0.000214, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=9773101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=2.465200, depth_time=2026-10-19T01:30:21+00:00, book20_bid_proxy_usdt=20661, book20_ask_proxy_usdt=8502, funding_indicative=-0.000430, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.17%, turnover=22483494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=0.085750, depth_time=2026-10-19T01:30:13+00:00, book20_bid_proxy_usdt=430806, book20_ask_proxy_usdt=417993, funding_indicative=-0.000030, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=50733705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=0.193800, depth_time=2026-10-19T01:30:15+00:00, book20_bid_proxy_usdt=145548, book20_ask_proxy_usdt=153623, funding_indicative=0.000001, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=7721221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=0.114571, depth_time=2026-10-19T01:30:08+00:00, book20_bid_proxy_usdt=6616, book20_ask_proxy_usdt=6192, funding_indicative=0.000097, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.98%, turnover=9745289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T01:29:59+00:00, last15m_closed_end=2026-10-19T01:30+00:00, prior8high=0.061290, depth_time=2026-10-19T01:30:19+00:00, book20_bid_proxy_usdt=636806, book20_ask_proxy_usdt=315459, funding_indicative=0.000032, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=17027149. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
